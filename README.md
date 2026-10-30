# Forward Networks

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Forward Networks builds network digital-twin software (Forward Enterprise) that creates a mathematically accurate, vendor-agnostic model of large hybrid and multi-cloud networks. Networking, security, cloud, and compliance teams use it to verify network behavior before and after changes, trace packet paths, run automated policy checks, analyze CVE/vulnerability exposure, and query the network as structured data through the Network Query Engine (NQE). The Forward Enterprise Complete API is an OpenAPI 3.2.0 surface of 189 operations across 108 paths — covering Networks, Snapshots, Checks, Path Search, NQE, Vulnerability Analysis, and system administration — secured with HTTP Basic authentication and complemented by a Go client, a Terraform provider, and an open-source MCP server.

**Areas:** Company · Networks · Network Automation · Network Digital Twin · Network Security · Network Verification · Path Analysis · Vulnerability Management · NQE · Compliance

## Forward Networks on APIs.io

Everything profiled for Forward Networks is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/forward-networks/](https://apis.io/providers/forward-networks/)** — or go straight to one of the APIs or properties below.

### APIs (20)

- [Forward Networks Aliases API](https://apis.io/apis/forward-networks/forward-networks-aliases-api/) — Define groups of network infrastructure elements or packet header values
- [Forward Networks Checks API](https://apis.io/apis/forward-networks/forward-networks-checks-api/) — Enable or define automated checks that verify network policy and behavior
- [Forward Networks Classic Devices API](https://apis.io/apis/forward-networks/forward-networks-classic-devices-api/) — Specify the network devices to collect from and model
- [Forward Networks Credentials API](https://apis.io/apis/forward-networks/forward-networks-credentials-api/) — Provide network device credentials needed for network collection
- [Forward Networks Current Version API](https://apis.io/apis/forward-networks/forward-networks-current-version-api/) — Get current API version information
- [Forward Networks Device Tags API](https://apis.io/apis/forward-networks/forward-networks-device-tags-api/) — List or manage tags associated with network devices and endpoints
- [Forward Networks Jump Servers API](https://apis.io/apis/forward-networks/forward-networks-jump-servers-api/) — Configure jump servers to assist in reaching network devices
- [Forward Networks Network Collection API](https://apis.io/apis/forward-networks/forward-networks-network-collection-api/) — Configure configuration and state collection from network devices
- [Forward Networks Network Devices API](https://apis.io/apis/forward-networks/forward-networks-network-devices-api/) — List the modeled network devices
- [Forward Networks Network Endpoints API](https://apis.io/apis/forward-networks/forward-networks-network-endpoints-api/) — Configure network endpoint profiles and specify the network endpoints to collect from
- [Forward Networks Network Locations API](https://apis.io/apis/forward-networks/forward-networks-network-locations-api/) — Get, create, update, or delete a network's user-defined locations
- [Forward Networks Network Snapshots API](https://apis.io/apis/forward-networks/forward-networks-network-snapshots-api/) — List or manage the network Snapshots collected from network devices
- [Forward Networks Network Topology API](https://apis.io/apis/forward-networks/forward-networks-network-topology-api/) — List the links inferred between network devices and override them if necessary
- [Forward Networks API](https://apis.io/apis/forward-networks/forward-networks-networks-api/) — Create, list, rename, or delete model networks
- [Forward Networks NQE API](https://apis.io/apis/forward-networks/forward-networks-nqe-api/) — Ask the Network Query Engine for structured, vendor-agnostic network information
- [Forward Networks Path Search API](https://apis.io/apis/forward-networks/forward-networks-path-search-api/) — Trace packets through the network model
- [Forward Networks Synthetic Devices API](https://apis.io/apis/forward-networks/forward-networks-synthetic-devices-api/) — Model a network’s internet connections, intranets, L2VPNs, L3VPNs, WAN circuits, and encryptors
- [Forward Networks System Administration API](https://apis.io/apis/forward-networks/forward-networks-system-administration-api/) — Administer the system, including database backups
- [Forward Networks User Accounts API](https://apis.io/apis/forward-networks/forward-networks-user-accounts-api/) — Manage user accounts
- [Forward Networks Vulnerability Analysis API](https://apis.io/apis/forward-networks/forward-networks-vulnerability-analysis-api/) — Identify network devices potentially impacted by CVEs

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [forward-mcp](https://apis.io/servers/forward-networks/forward-mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Forward Networks Agentic Access](https://apis.io/agentic-access/forward-networks/forward-networks-agentic-access/)

#### Collections (20)

Postman and Open Collection request collections.

- [Forward Networks: Complete Aliases API](https://apis.io/collections/forward-networks/open-forward-networks-aliases-api/)
- [Forward Networks: Complete Aliases Checks API](https://apis.io/collections/forward-networks/open-forward-networks-checks-api/)
- [Forward Networks: Complete Aliases Classic Devices API](https://apis.io/collections/forward-networks/open-forward-networks-classic-devices-api/)
- [Forward Networks: Complete Aliases Credentials API](https://apis.io/collections/forward-networks/open-forward-networks-credentials-api/)
- [Forward Networks: Complete Aliases Current Version API](https://apis.io/collections/forward-networks/open-forward-networks-current-version-api/)
- [Forward Networks: Complete Aliases Device Tags API](https://apis.io/collections/forward-networks/open-forward-networks-device-tags-api/)
- [Forward Networks: Complete Aliases Jump Servers API](https://apis.io/collections/forward-networks/open-forward-networks-jump-servers-api/)
- [Forward Networks: Complete Aliases Network Collection API](https://apis.io/collections/forward-networks/open-forward-networks-network-collection-api/)
- [Forward Networks: Complete Aliases Network Devices API](https://apis.io/collections/forward-networks/open-forward-networks-network-devices-api/)
- [Forward Networks: Complete Aliases Network Endpoints API](https://apis.io/collections/forward-networks/open-forward-networks-network-endpoints-api/)
- [Forward Networks: Complete Aliases Network Locations API](https://apis.io/collections/forward-networks/open-forward-networks-network-locations-api/)
- [Forward Networks: Complete Aliases Network Snapshots API](https://apis.io/collections/forward-networks/open-forward-networks-network-snapshots-api/)
- [Forward Networks: Complete Aliases Network Topology API](https://apis.io/collections/forward-networks/open-forward-networks-network-topology-api/)
- [Forward : Complete Aliases Networks API](https://apis.io/collections/forward-networks/open-forward-networks-networks-api/)
- [Forward Networks: Complete Aliases NQE API](https://apis.io/collections/forward-networks/open-forward-networks-nqe-api/)
- [Forward Networks: Complete Aliases Path Search API](https://apis.io/collections/forward-networks/open-forward-networks-path-search-api/)
- [Forward Networks: Complete Aliases Synthetic Devices API](https://apis.io/collections/forward-networks/open-forward-networks-synthetic-devices-api/)
- [Forward Networks: Complete Aliases System Administration API](https://apis.io/collections/forward-networks/open-forward-networks-system-administration-api/)
- [Forward Networks: Complete Aliases User Accounts API](https://apis.io/collections/forward-networks/open-forward-networks-user-accounts-api/)
- [Forward Networks: Complete Aliases Vulnerability Analysis API](https://apis.io/collections/forward-networks/open-forward-networks-vulnerability-analysis-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Forward Networks Complete Overlay](https://apis.io/overlays/forward-networks/forward-networks-complete-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Forward Networks Authentication](https://apis.io/security/forward-networks/forward-networks-authentication/)
- [Forward Networks Domain Security](https://apis.io/security/forward-networks/forward-networks-domain-security/)
- [Forward Networks Trust Center](https://apis.io/security/forward-networks/forward-networks-trust-center/)
- [Forward Networks Vulnerability Disclosure](https://apis.io/security/forward-networks/forward-networks-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.forwardnetworks.com/)
- [Documentation](https://docs.fwd.app/)
- [Pricing](https://www.forwardnetworks.com/pricing/)
- [Sign up](https://fwd.app/)
- [Blog](https://www.forwardnetworks.com/blog/)
- [Security](https://www.forwardnetworks.com/.well-known/security.txt)
- [Compliance](https://www.forwardnetworks.com/compliance/)
- [Terms of service](https://www.forwardnetworks.com/master-services-agreement/)
- [Privacy policy](https://www.forwardnetworks.com/privacy-policy/)
- [GitHub](https://github.com/forwardnetworks)

## API Evangelist rating

**Kin Score 43.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 45.6 |
| Contract governance | 4.5 |
| Operational transparency | 7.9 |
| Developer ergonomics | 39.9 |
| Access clarity | 47.4 |

**Agent readiness 31.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/forward-networks/](https://apis.io/providers/forward-networks/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Forward Networks: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/forward-networks/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
