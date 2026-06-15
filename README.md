# Lit Protocol (lit-protocol)

Lit Protocol is a decentralized key management network providing Programmable Key Pairs (PKPs), Lit Actions (off-chain JS execution), threshold encryption, and access-control conditions. The Chipotle Express API exposes account, PKP, and Lit Action management as REST endpoints alongside the JavaScript SDK.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lit-protocol/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lit-protocol/refs/heads/main/apis.yml)

## Tags

- Web3
- Key Management
- MPC
- Programmable Keys
- Lit Actions

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Lit Protocol Chipotle Express API (Core v1)

REST API for account management, API keys, PKP minting, IPFS-anchored Lit Actions, encryption/decryption helpers, and credit balance / usage queries.

- **Human URL:** [https://developer.litprotocol.com/](https://developer.litprotocol.com/)
- **Base URL:** `https://api.chipotle.litprotocol.com/core/v1`

#### Tags

- REST
- PKP
- Lit Actions

#### Properties

- [Documentation](https://developer.litprotocol.com/)
- [OpenAPI](openapi/lit-protocol-core-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lit-protocol-core-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lit-protocol-core-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lit Network Node JSON-RPC (SDK-mediated)

Threshold-cryptography network of Lit nodes accessed via the Lit JS SDK for signing, encryption, decryption, and Lit Action execution. Direct REST access is via the Chipotle API; raw node JSON-RPC is documented for SDK contributors.

- **Human URL:** [https://developer.litprotocol.com/v3/sdk/installation](https://developer.litprotocol.com/v3/sdk/installation)
- **Base URL:** `https://serrano.litgateway.com/web/litaction (SDK-mediated)`

#### Tags

- JSON-RPC
- Network

#### Properties

- [Documentation](https://developer.litprotocol.com/v3/sdk/installation)
- [Postman Collection](collections/lit-protocol-core-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lit-protocol-core-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/LIT-Protocol)
- [LinkedIn](https://www.linkedin.com/company/lit-protocol)
- [Website](https://www.litprotocol.com/)
- [Plans](plans/lit-protocol-plans-pricing.yml)
- [Rate Limits](rate-limits/lit-protocol-rate-limits.yml)
- [Fin Ops](finops/lit-protocol-finops.yml)
- [L L Ms Txt](https://developer.litprotocol.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
