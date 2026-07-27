---
name: Collect a snapshot and run network checks
description: Create a Forward Networks snapshot of a network and run automated policy/behavior checks against it.
api: openapi/forward-networks-complete-openapi-original.json
operations: [getNetworks, createSnapshot, getLatestProcessedSnapshot, getAvailablePredefinedChecks, addCheck, getChecks]
---

# Collect a snapshot and run checks

## Auth
HTTP Basic (`api_token`). See `authentication/forward-networks-authentication.yml`.

## Steps
1. Resolve the network with `getNetworks` (`GET /networks`).
2. Kick off collection with `createSnapshot` (`POST /networks/{networkId}/snapshots`).
3. Snapshot processing is asynchronous — poll `getLatestProcessedSnapshot` (`GET /networks/{networkId}/snapshots/latestProcessed`) until the snapshot is processed (operations against a processing snapshot return `409`).
4. Browse available predefined checks with `getAvailablePredefinedChecks` (`GET /predefinedChecks`).
5. Add a check to the snapshot with `addCheck` (`POST /snapshots/{snapshotId}/checks`).
6. Read check results with `getChecks` (`GET /snapshots/{snapshotId}/checks`).

## Notes
- Always operate against a processed snapshot; the `409` conflict is the async-processing signal (see `conventions/forward-networks-conventions.yml`).
