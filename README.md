# Nishant Agarwal

**Software / Backend Engineer** · open-source contributor to ClickHouse, Hardhat, viem, WalletConnect, Mastra

B.Tech CSE @ Bennett University · Web3 intern @ Digital South Trust · India

[Portfolio](https://nishantx.in) · [Resume (PDF)](./resume.pdf) · [LinkedIn](https://www.linkedin.com/in/nishant-agarwal-62a956322/) · [Email](mailto:agarwalnishant812@gmail.com)

---

## About

I build backend systems and developer infrastructure — REST APIs, distributed storage patterns, smart-contract integrations, and production bug fixes in large open-source codebases. I also ship full-stack products with live deployments, automated tests, and documented architecture.

**Research:** *BlockForge* — accepted at [NetCrypt 2026](https://github.com/nishant-uxs/labeval) (4th International Conference on Networks and Cryptology).

---

## Selected open source contributions

Merged upstream only. Full list: [OPEN_SOURCE.md](./OPEN_SOURCE.md).

| Project | PR | What changed |
|---------|-----|--------------|
| **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** | [#114003](https://github.com/ClickHouse/ClickHouse/pull/114003) | Fixed Keeper `writeAt` durability ordering so cross-segment Raft log truncation no longer leaves stale changelog segments that brick startup with `CORRUPTED_DATA` (closes [#112101](https://github.com/ClickHouse/ClickHouse/issues/112101)). |
| **[Hardhat](https://github.com/NomicFoundation/hardhat)** | [#8464](https://github.com/NomicFoundation/hardhat/pull/8464) | Configuration variables now prefer `process.env` over plugin hooks / keystore; added unit tests for hook short-circuiting. |
| **[viem](https://github.com/wevm/viem)** | [#4903](https://github.com/wevm/viem/pull/4903) | Fixed ESM `_types` package generation for TypeScript `NodeNext` module resolution. |
| **[WalletConnect](https://github.com/WalletConnect/walletconnect-monorepo)** | [#7302](https://github.com/WalletConnect/walletconnect-monorepo/pull/7302) | Added `@types/node` annotations on `EventEmitter` usage. |
| **[Mastra](https://github.com/mastra-ai/mastra)** | [#20487](https://github.com/mastra-ai/mastra/pull/20487), [#20518](https://github.com/mastra-ai/mastra/pull/20518) | Skip execution of declined tools; reuse terminal nested workflow snapshots. |
| **[Hyperlane](https://github.com/hyperlane-xyz/hyperlane-monorepo)** | [#9181](https://github.com/hyperlane-xyz/hyperlane-monorepo/pull/9181) | Hardened `HyperlaneMessage::from` to avoid panics on malformed multi-chain payloads. |
| **[FilOzone](https://github.com/FilOzone/pdp)** | [#287](https://github.com/FilOzone/pdp/pull/287) + [filecoin-services #566](https://github.com/FilOzone/filecoin-services/pull/566) | Emit `PiecesScheduledForRemoval` and wire PDPVerifier ABI/event. |
| **[hardhat-website](https://github.com/NomicFoundation/hardhat-website)** | [#288](https://github.com/NomicFoundation/hardhat-website/pull/288) | Document Node.js minimum version v22.13.0. |

### Open PRs (in progress)

| Project | PR | Status |
|---------|-----|--------|
| [ClickHouse](https://github.com/ClickHouse/ClickHouse) | [#113934](https://github.com/ClickHouse/ClickHouse/pull/113934) | Open — MergeTree MODIFY TTL mutation wedge after crash |
| [dotnet/runtime](https://github.com/dotnet/runtime) | [#132655](https://github.com/dotnet/runtime/pull/132655) | Open — ThreadPool dispatch finishing an already-completed Task |
| [Nethermind](https://github.com/NethermindEth/nethermind) | [#12739](https://github.com/NethermindEth/nethermind/pull/12739) | Open — `eth_syncing` highest block includes beacon tip |
| [OpenZeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) | [#6639](https://github.com/OpenZeppelin/openzeppelin-contracts/pull/6639) | Open — IERC1967-Upgraded NatSpec in UUPSUpgradeable |
| [LiteLLM](https://github.com/BerriAI/litellm) | [#35349](https://github.com/BerriAI/litellm/pull/35349) | Open — partial usage recovery on sync mid-stream failure |

---

## Selected projects

| Project | Summary | Links |
|---------|---------|-------|
| **[Krydo](https://github.com/nishant-uxs/krydo)** | Privacy-preserving credentials on Ethereum — sigma-protocol ZK proofs over Pedersen commitments, Express API, SIWE auth, Firestore query layer, 154 Vitest tests, 3 Sepolia contracts. | [Live](https://krydo.onrender.com) |
| **[BlockForge / LabEval](https://github.com/nishant-uxs/labeval)** | Decentralized lab assessment — OpenZeppelin RBAC, IPFS CIDs on-chain (~92% storage reduction vs full on-chain artifacts), Gemini-assisted grading. NetCrypt 2026 paper. | [Live](https://blockchain-labeval.onrender.com) |
| **[CivicSense](https://github.com/nishant-uxs/CivicSense)** | Civic reporting platform — 3-step on-chain lifecycle, hybrid Supabase + Sepolia storage, 10 API route groups, Gemini triage. | [Live](https://civic-sense-six.vercel.app) |
| **[CommitLock](https://github.com/nishant-uxs/CommitLock)** | No-show protection on Stellar Soroban — refundable XLM escrow, fee-bump sponsorship, Horizon event indexing, metrics dashboard. | [Live](https://commitlock.onrender.com) |
| **[TrustMesh](https://github.com/nishant-uxs/TrustMesh)** | Business trust network on Stellar Soroban — reputation scoring, multi-contract Testnet deployment. | [Live](https://trust-mesh-taupe.vercel.app) |
| **[gov-crypto-intel-hub](https://github.com/nishant-uxs/gov-crypto-intel-hub)** | Government crypto intelligence dashboard — Next.js, Prisma, Claude API integration. | [Live](https://gov-crypto-intel-hub.vercel.app) |

---

## Technical stack

**Languages:** TypeScript, JavaScript, Python, Solidity, Rust, C++, SQL

**Backend:** Node.js, Express, REST APIs, Zod validation, JWT/SIWE auth, PostgreSQL (Supabase), Firestore

**Systems / infra:** ClickHouse Keeper, distributed storage, IPFS, CI (GitHub Actions), Docker

**Blockchain:** Ethereum (Hardhat, ethers/viem), Stellar Soroban, Filecoin PDP, ZK proofs (sigma protocols)

**Frontend:** React, Vite, Tailwind, shadcn/ui

---

## Contact

- GitHub: [@nishant-uxs](https://github.com/nishant-uxs)
- Portfolio: [nishantx.in](https://nishantx.in)
- Email: agarwalnishant812@gmail.com
