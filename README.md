# Kroger

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

The Kroger Co. is the largest supermarket operator in the United States and runs a two-tier developer programme from developer.kroger.com. The Public tier is self-service after account and application registration and covers Products, Locations, Identity and Cart, each with a published daily call quota. The Partner tier — Carts, Catalog, Catalog V2, Identity, Locations, Products, Seamless Delivery and Locker Integration — is not self-service and requires a signed contractual agreement with Kroger. Every API is protected by OAuth 2.0 at api.kroger.com, with client-credentials access for catalogue and store data and authorization-code access, with explicit customer consent, for anything that touches a shopper's profile or cart. A separate certification environment runs at api-ce.kroger.com.

**Areas:** Groceries · Grocery Retail · Retail · E-Commerce · Product Catalog · Store Locations · Shopping Cart · Loyalty · Authentication · Partner API · Fortune 100

## Kroger on APIs.io

Everything profiled for Kroger is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kroger/](https://apis.io/providers/kroger/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Kroger Authorization API (Partners)](https://apis.io/apis/kroger/kroger-authorization-api-partners/) — The authorization endpoints provide a token that will allow your service or application to call Kroger APIs.
- [Kroger Authorization API (Public)](https://apis.io/apis/kroger/kroger-authorization-api-public/) — The authorization endpoints provide a token that will allow your service or application to call Kroger APIs.
- [Kroger Cart API (Partner)](https://apis.io/apis/kroger/kroger-cart-api-partner/) — The Carts API provides access to create, view, and update a customers cart.
- [Kroger Cart API (Public)](https://apis.io/apis/kroger/kroger-cart-api-public/) — The Cart API allows you to add an item to an authenticated customers cart.
- [Kroger Catalog API](https://apis.io/apis/kroger/kroger-catalog-api/) — Catalog API integration let partners to access Krogers catalog data via available product endpoints. The catalog can be customized for the partners based on…
- [Kroger Catalog API V2](https://apis.io/apis/kroger/kroger-catalog-api-v2/) — Catalog API integration let partners to access Krogers catalog data via available product endpoints. The catalog can be customized for the partners based on…
- [Kroger Identity API](https://apis.io/apis/kroger/kroger-identity-api/) — The Identity API provides access to the profile information of an authenticated Kroger customer.
- [Kroger Identity API (Public)](https://apis.io/apis/kroger/kroger-identity-api-public/) — The Identity API allows you to access the profile ID of an authenticated customer.
- [Kroger Location API (Partner)](https://apis.io/apis/kroger/kroger-location-api-partner/) — Partner APIs enable official partners to access strategic functionality and data. Since the needs of our partners determine our Partner APIs, they are not…
- [Kroger Location API (Public)](https://apis.io/apis/kroger/kroger-location-api-public/) — The Locations API provides access to all locations, chains, and departments that are owned by The Kroger Co.
- [Kroger Products API (Partners)](https://apis.io/apis/kroger/kroger-products-api-partners/) — The Products API allows you to search the Kroger product catalog.Pagination.
- [Kroger Products API (Public)](https://apis.io/apis/kroger/kroger-products-api-public/) — The Products API allows you to search the Kroger product catalog.
- [Kroger Seamless Delivery API](https://apis.io/apis/kroger/kroger-seamless-delivery-api/) — Partner APIs related to integrating with a full-service delivery partner.
- [Kroger Locker Integration APIs (Partners)](https://apis.io/apis/kroger/kroger-locker-integration-apis-partners/) — This contract outlines the APIs agreement for vendors seeking integration with Kroger as a locker vendor. The provided APIs enable partners to transmit…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Kroger MCP Candidate](https://apis.io/servers/kroger/kroger-mcp-candidate/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Kroger Authentication](https://apis.io/security/kroger/kroger-authentication/)
- [Kroger Domain Security](https://apis.io/security/kroger/kroger-domain-security/)
- [Kroger Vulnerability Disclosure](https://apis.io/security/kroger/kroger-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Kroger Scopes](https://apis.io/scopes/kroger/kroger-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kroger Plans Pricing](https://apis.io/plans/kroger/kroger-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kroger Rate Limits](https://apis.io/rate-limits/kroger/kroger-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Kroger Finops](https://apis.io/finops/kroger/kroger-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://kroger.com)
- [Documentation](https://developer.kroger.com/documentation/public/getting-started/apis)
- [Getting started](https://developer.kroger.com/documentation/public/getting-started/quick-start)
- [API reference](https://developer.kroger.com/reference)
- [Support](https://developer.kroger.com/documentation/support/api-troubleshooting/troubleshooting)
- [Security](https://bugcrowd.com/engagements/kroger-vdp)
- [Terms of service](https://developer.kroger.com/documentation/public/getting-started/acceptable-use)
- [Privacy policy](https://www.kroger.com/i/privacy-policy)
- [GitHub](https://github.com/krogertechnology)

## API Evangelist rating

**Kin Score 41.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 44.7 |
| Developer ergonomics | 66.7 |
| Access clarity | 42.1 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 40.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kroger/](https://apis.io/providers/kroger/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kroger: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kroger/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
