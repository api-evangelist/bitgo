# BitGo (bitgo)

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
