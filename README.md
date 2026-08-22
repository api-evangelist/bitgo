# BitGo (bitgo)

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

BitGo is an institutional digital-asset custody, wallet, staking, trading, and settlement infrastructure provider and qualified custodian. The BitGo Platform REST API v2 lets developers programmatically create and manage multi-signature and advanced-cryptography wallets, addresses, keychains, transactions and transfers, webhooks, spending policies, staking, and Go Network off-chain settlement across hundreds of coins and tokens, with an optional self-hosted Express signing proxy.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bitgo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bitgo/refs/heads/main/apis.yml)

## Tags

- Digital Assets
- Custody
- Wallets
- Blockchain
- Crypto
- Staking
- Settlement

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### BitGo Wallets API

Create, list, retrieve, and manage multi-signature and TSS wallets per coin, including balances, wallet limits, and enterprise assignment across BitGo's hot, cold, and custodial wallet types.

- **Human URL:** [https://developers.bitgo.com/api/express.generatewallet](https://developers.bitgo.com/api/express.generatewallet)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Wallets
- Multi-Signature
- Custody

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/express.generatewallet)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Addresses API

Generate and manage deposit addresses on a wallet, list existing addresses, and retrieve address details and balances for receiving on-chain funds.

- **Human URL:** [https://developers.bitgo.com/api/express.createwalletaddress](https://developers.bitgo.com/api/express.createwalletaddress)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Addresses
- Deposits
- Wallets

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/express.createwalletaddress)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Transactions & Transfers API

Build, sign, and send single or batched on-chain transactions, and list and retrieve transfers (the BitGo record of a wallet's inbound and outbound value movement) with confirmations, state, and metadata.

- **Human URL:** [https://developers.bitgo.com/api/express.sendcoins](https://developers.bitgo.com/api/express.sendcoins)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Transactions
- Transfers
- Payments

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/express.sendcoins)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Keychains & Keys API

Create and manage the user, backup, and BitGo keychains that back multi-signature wallets, including public-key registration and encrypted private-key material.

- **Human URL:** [https://developers.bitgo.com/api/v2.keychain.list](https://developers.bitgo.com/api/v2.keychain.list)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Keys
- Keychains
- Cryptography

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/v2.keychain.list)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Webhooks API

Register, list, and remove wallet- and block-level webhooks that notify your systems of transfers, confirmations, address confirmations, and pending approvals via HTTP callbacks.

- **Human URL:** [https://developers.bitgo.com/api/v2.wallet.addwebhook](https://developers.bitgo.com/api/v2.wallet.addwebhook)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/v2.wallet.addwebhook)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Wallet Policies API

Define and update on-wallet spending policies - velocity limits, per-transaction caps, whitelists, and multi-user approval rules - and manage the pending-approval workflow they trigger.

- **Human URL:** [https://developers.bitgo.com/api/v2.wallet.updatepolicy](https://developers.bitgo.com/api/v2.wallet.updatepolicy)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Policies
- Governance
- Approvals

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/v2.wallet.updatepolicy)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Staking API

Programmatically stake and unstake supported proof-of-stake assets from a wallet, list staking requests and delegations, and track rewards across supported networks.

- **Human URL:** [https://developers.bitgo.com/api/staking.stake](https://developers.bitgo.com/api/staking.stake)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Staking
- Rewards
- Proof of Stake

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/staking.stake)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Trading & Settlement (Go Network) API

Access trading accounts and off-chain settlement over the BitGo Go Network, listing settlements and trades between counterparties without moving assets on-chain.

- **Human URL:** [https://developers.bitgo.com/api/trading.settlement.list](https://developers.bitgo.com/api/trading.settlement.list)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Trading
- Settlement
- Go Network

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/trading.settlement.list)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Express API

Self-hosted REST proxy (a Docker container or Node service) that performs local private-key handling and transaction signing so sensitive key material never leaves your infrastructure while proxying calls to the BitGo platform.

- **Human URL:** [https://developers.bitgo.com/api/express](https://developers.bitgo.com/api/express)
- **Base URL:** `http://localhost:3080/api/v2`

#### Tags

- Express
- Signing Proxy
- Self-Hosted

#### Properties

- [Documentation](https://developers.bitgo.com/api/express)
- [API Reference](https://developers.bitgo.com/api/express)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BitGo Enterprise & Users API

Manage enterprises (the top-level organizational account), list their wallets and users, and retrieve the authenticated user session and profile.

- **Human URL:** [https://developers.bitgo.com/api/v2.enterprise.list](https://developers.bitgo.com/api/v2.enterprise.list)
- **Base URL:** `https://app.bitgo.com/api/v2`

#### Tags

- Enterprise
- Users
- Accounts

#### Properties

- [Documentation](https://developers.bitgo.com/api)
- [API Reference](https://developers.bitgo.com/api/v2.enterprise.list)
- [OpenAPI](openapi/bitgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bitgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bitgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/BitGo)
- [LinkedIn](https://www.linkedin.com/company/bitgo)
- [Website](https://www.bitgo.com/)
- [Documentation](https://developers.bitgo.com/)
- [Plans](plans/bitgo-plans-pricing.yml)
- [Rate Limits](rate-limits/bitgo-rate-limits.yml)
- [Fin Ops](finops/bitgo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
