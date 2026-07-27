---
name: Run a Network Query Engine (NQE) query
description: Ask Forward Networks' Network Query Engine for structured, vendor-agnostic network data and retrieve the results.
api: openapi/forward-networks-complete-openapi-original.json
operations: [getNqeQueries, runNqeQuery, addNqeQueryExecution, getNqeExecutionStatus, getNqeExecutionResult]
---

# Run an NQE query

Use the Network Query Engine (NQE) to query the network model as structured data.

## Auth
HTTP Basic (`api_token`): send a Forward Enterprise username/password or API token. See `authentication/forward-networks-authentication.yml`.

## Steps
1. (Optional) List saved queries with `getNqeQueries` (`GET /nqe/queries`) to find a query ID, or supply raw NQE query text.
2. For a synchronous run, call `runNqeQuery` (`POST /nqe`) with the query and a target `networkId`/`snapshotId`.
3. For long-running work, start an async execution with `addNqeQueryExecution` (`POST /networks/{networkId}/nqe-executions`), which returns an `executionKey`.
4. Poll `getNqeExecutionStatus` (`GET /networks/{networkId}/nqe-executions/{executionKey}`) until complete.
5. Fetch results with `getNqeExecutionResult` (`GET /networks/{networkId}/nqe-executions/{executionKey}/result`).

## Notes
- A `400` on a query means a parse/execution error; the `errors` array carries line numbers (see `errors/forward-networks-problem-types.yml`).
- A `409` means the target snapshot is still processing; poll `getLatestProcessedSnapshot` first.
- Results paginate with `offset`/`limit` (see `conventions/forward-networks-conventions.yml`).
