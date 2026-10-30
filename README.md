# Lit Protocol

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

Lit Protocol is a decentralized key management network providing Programmable Key Pairs (PKPs), Lit Actions (off-chain JS execution), threshold encryption, and access-control conditions. The Chipotle Express API exposes account, PKP, and Lit Action management as REST endpoints alongside the JavaScript SDK.

**Areas:** Web3 · Key Management · MPC · Programmable Keys · Lit Actions

## Lit Protocol on APIs.io

Everything profiled for Lit Protocol is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lit-protocol/](https://apis.io/providers/lit-protocol/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Lit Network Node JSON-RPC (SDK-mediated)](https://apis.io/apis/lit-protocol/network-rpc/) — Threshold-cryptography network of Lit nodes accessed via the Lit JS SDK for signing, encryption, decryption, and Lit Action execution. Direct REST access is…
- [Lit Protocol Account Management API](https://apis.io/apis/lit-protocol/lit-protocol-account-management-api/) — The Account Management API from Lit Protocol — 28 operation(s) for account management.
- [Lit Protocol Actions API](https://apis.io/apis/lit-protocol/lit-protocol-actions-api/) — The Actions API from Lit Protocol — 1 operation(s) for actions.
- [Lit Protocol Billing API](https://apis.io/apis/lit-protocol/lit-protocol-billing-api/) — The Billing API from Lit Protocol — 4 operation(s) for billing.
- [Lit Protocol Configuration API](https://apis.io/apis/lit-protocol/lit-protocol-configuration-api/) — The Configuration API from Lit Protocol — 4 operation(s) for configuration.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lit Protocol Agentic Access](https://apis.io/agentic-access/lit-protocol/lit-protocol-agentic-access/)

#### JSON Schema (40)

The data models the API reads and writes.

- [AccountOpResponse](https://apis.io/schemas/lit-protocol/lit-protocol-accountopresponse/)
- [AddActionRequest](https://apis.io/schemas/lit-protocol/lit-protocol-addactionrequest/)
- [AddActionToGroupRequest](https://apis.io/schemas/lit-protocol/lit-protocol-addactiontogrouprequest/)
- [AddGroupRequest](https://apis.io/schemas/lit-protocol/lit-protocol-addgrouprequest/)
- [AddGroupResponse](https://apis.io/schemas/lit-protocol/lit-protocol-addgroupresponse/)
- [AddPkpToGroupRequest](https://apis.io/schemas/lit-protocol/lit-protocol-addpkptogrouprequest/)
- [AddUsageApiKeyRequest](https://apis.io/schemas/lit-protocol/lit-protocol-addusageapikeyrequest/)
- [AddUsageApiKeyResponse](https://apis.io/schemas/lit-protocol/lit-protocol-addusageapikeyresponse/)
- [AddUsageApiKeyWithSignatureRequest](https://apis.io/schemas/lit-protocol/lit-protocol-addusageapikeywithsignaturerequest/)
- [AddUsageApiKeyWithSignatureResponse](https://apis.io/schemas/lit-protocol/lit-protocol-addusageapikeywithsignatureresponse/)
- [ApiKeyItem](https://apis.io/schemas/lit-protocol/lit-protocol-apikeyitem/)
- [BillingBalanceResponse](https://apis.io/schemas/lit-protocol/lit-protocol-billingbalanceresponse/)
- [ChainConfigKeysResponse](https://apis.io/schemas/lit-protocol/lit-protocol-chainconfigkeysresponse/)
- [ConfirmPaymentRequest](https://apis.io/schemas/lit-protocol/lit-protocol-confirmpaymentrequest/)
- [ConvertToChainSecuredAccountRequest](https://apis.io/schemas/lit-protocol/lit-protocol-converttochainsecuredaccountrequest/)
- [CreatePaymentIntentRequest](https://apis.io/schemas/lit-protocol/lit-protocol-createpaymentintentrequest/)
- [CreatePaymentIntentResponse](https://apis.io/schemas/lit-protocol/lit-protocol-createpaymentintentresponse/)
- [CreateWalletResponse](https://apis.io/schemas/lit-protocol/lit-protocol-createwalletresponse/)
- [CreateWalletWithSignatureRequest](https://apis.io/schemas/lit-protocol/lit-protocol-createwalletwithsignaturerequest/)
- [CreateWalletWithSignatureResponse](https://apis.io/schemas/lit-protocol/lit-protocol-createwalletwithsignatureresponse/)
- [DeleteActionRequest](https://apis.io/schemas/lit-protocol/lit-protocol-deleteactionrequest/)
- [ErrMessage](https://apis.io/schemas/lit-protocol/lit-protocol-errmessage/)
- [ListMetadataItem](https://apis.io/schemas/lit-protocol/lit-protocol-listmetadataitem/)
- [LitActionClientConfigResponse](https://apis.io/schemas/lit-protocol/lit-protocol-litactionclientconfigresponse/)
- [LitActionRequest](https://apis.io/schemas/lit-protocol/lit-protocol-litactionrequest/)
- …and 15 more published on APIs.io

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Lit Protocol Structure](https://apis.io/json-structure/lit-protocol/lit-protocol-structure/)

#### Collections (5)

Postman and Open Collection request collections.

- [lit-api-server Account Management API](https://apis.io/collections/lit-protocol/open-lit-protocol-account-management-api/)
- [lit-api-server Account Management Actions API](https://apis.io/collections/lit-protocol/open-lit-protocol-actions-api/)
- [lit-api-server Account Management Billing API](https://apis.io/collections/lit-protocol/open-lit-protocol-billing-api/)
- [lit-api-server Account Management Configuration API](https://apis.io/collections/lit-protocol/open-lit-protocol-configuration-api/)
- [lit-api-server](https://apis.io/collections/lit-protocol/open-lit-protocol-core-v1/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Lit Protocol — jsonschema rules](https://apis.io/rules/lit-protocol/lit-protocol-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Lit Protocol Domain Security](https://apis.io/security/lit-protocol/lit-protocol-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lit Protocol Plans Pricing](https://apis.io/plans/lit-protocol/lit-protocol-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lit Protocol Rate Limits](https://apis.io/rate-limits/lit-protocol/lit-protocol-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Lit Protocol Finops](https://apis.io/finops/lit-protocol/lit-protocol-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.litprotocol.com/)
- [Blog](https://spark.litprotocol.com/rss/)
- [GitHub](https://github.com/LIT-Protocol)

## API Evangelist rating

**Kin Score 19.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 33.1 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 11.9 |
| Access clarity | 5.3 |

**Agent readiness 15.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 5.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lit-protocol/](https://apis.io/providers/lit-protocol/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lit Protocol: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lit-protocol/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
