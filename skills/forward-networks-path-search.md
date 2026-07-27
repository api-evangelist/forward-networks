---
name: Trace a packet path through the network
description: Use Forward Networks Path Search to trace how packets traverse the modeled network between endpoints.
api: openapi/forward-networks-complete-openapi-original.json
operations: [getNetworks, getPaths, getPathsBulk, getL7Applications]
---

# Trace a packet path

Path Search traces packets through the network digital twin to verify reachability and security posture.

## Auth
HTTP Basic (`api_token`). See `authentication/forward-networks-authentication.yml`.

## Steps
1. Resolve the target network with `getNetworks` (`GET /networks`).
2. Trace a single path with `getPaths` (`GET /networks/{networkId}/paths`), passing source/destination and packet-header parameters.
3. For many source/destination pairs, use `getPathsBulk` (`POST /networks/{networkId}/paths-bulk`).
4. (Optional) Enrich with L7 application context via `getL7Applications` (`GET /l7-applications`).

## Notes
- A `409` indicates the snapshot is still processing; confirm a processed snapshot first.
- See `conventions/forward-networks-conventions.yml` for pagination and error semantics.
