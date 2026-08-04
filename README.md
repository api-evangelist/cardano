# Cardano (cardano)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
