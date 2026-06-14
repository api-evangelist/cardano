# Cardano (cardano)

Cardano is a proof-of-stake blockchain platform designed for secure and scalable decentralized applications and smart contracts. Developer API access to the Cardano network is provided primarily through Blockfrost, a hosted REST API service that exposes over 100 endpoints covering transactions, addresses, assets, blocks, epochs, stake pools, governance, scripts, metadata, and mempool data. Authentication uses project-scoped API keys passed as HTTP headers. Blockfrost operates on Cardano Mainnet, Preview, and Pre-Production testnets, and also supports IPFS storage and the Milkomeda sidechain. SDKs are available for 15+ programming languages.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cardano/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cardano/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Blockchain
- Cryptocurrency
- Proof-of-Stake
- Smart Contracts
- Web3

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Blockfrost Cardano API

The Blockfrost Cardano API provides instant, highly optimized REST access to the Cardano blockchain without requiring developers to run their own node or manage infrastructure. The API covers over 100 endpoints across accounts, addresses, assets, blocks, epochs, governance, ledger state, mempool, metadata, network statistics, pools, scripts, transactions, and utilities. Authentication requires a `project_id` header obtained by registering at blockfrost.io.

- **Human URL:** [https://blockfrost.dev/start-building/cardano/](https://blockfrost.dev/start-building/cardano/)
- **Base URL:** `https://cardano-mainnet.blockfrost.io/api/v0`

#### Tags

- Blockchain
- Cardano
- Transactions
- Addresses
- Assets
- Blocks
- Epochs
- Pools
- Smart Contracts

#### Properties

| Type | URL |
|------|-----|
| Documentation | [https://blockfrost.dev/start-building/cardano/](https://blockfrost.dev/start-building/cardano/) |
| APIReference | [https://docs.blockfrost.io/](https://docs.blockfrost.io/) |
| Plans | [https://blockfrost.dev/overview/plans-and-billing](https://blockfrost.dev/overview/plans-and-billing) |
| Plans | [plans/cardano-plans-pricing.yml](plans/cardano-plans-pricing.yml) |
| RateLimits | [rate-limits/cardano-rate-limits.yml](rate-limits/cardano-rate-limits.yml) |
| FinOps | [finops/cardano-finops.yml](finops/cardano-finops.yml) |

### Blockfrost IPFS API

Blockfrost also operates as an IPFS provider, enabling developers building on Cardano to pin and retrieve content-addressed files via the InterPlanetary File System. The IPFS API uses the same `project_id` authentication as the Cardano mainnet API. Storage quota varies by subscription plan, from 100 MB on the free Starter tier to 50,000 MB on the Developer tier.

- **Human URL:** [https://blockfrost.dev/](https://blockfrost.dev/)
- **Base URL:** `https://ipfs.blockfrost.io/api/v0`

#### Tags

- Blockchain
- Cardano
- IPFS
- Storage
- Decentralized Storage

## Maintainers

**Kin Lane** — kin@apievangelist.com
