# Nishant Agarwal

**Backend systems · AI / blockchain infrastructure · open-source contributor**

B.Tech CSE, Bennett University (CGPA 8.86) · Web3 Intern @ Digital South Trust · India

Merged code into **[Hardhat](https://github.com/NomicFoundation/hardhat)** and **[viem](https://github.com/wevm/viem)** — production tooling used across the Ethereum ecosystem.

---

## Open Source

Upstream contributions to core developer infrastructure (merged only).

| Priority | Project | PR | What shipped |
|:---:|:---|:---|:---|
| ★ | **[NomicFoundation/hardhat](https://github.com/NomicFoundation/hardhat)** | [#8464](https://github.com/NomicFoundation/hardhat/pull/8464) | Prefer `process.env` when resolving configuration variables — env wins over plugin hooks (incl. keystore); unit tests included |
| ★ | **[wevm/viem](https://github.com/wevm/viem)** | [#4903](https://github.com/wevm/viem/pull/4903) | Fixed ESM `_types` package generation for TypeScript NodeNext compatibility |
| · | [NomicFoundation/hardhat-website](https://github.com/NomicFoundation/hardhat-website) | [#288](https://github.com/NomicFoundation/hardhat-website/pull/288) | Docs: Node.js minimum version aligned to v22.13.0 |

Full log → [`OPEN_SOURCE.md`](./OPEN_SOURCE.md)

---

## Engineering Impact

| Signal | Detail |
|:---|:---|
| **Upstream merges** | Hardhat core + viem (+ Hardhat docs) |
| **ZK system** | 6 sigma-protocol proofs · 154 unit tests · 3 Sepolia contracts · W3C VC export ([Krydo](https://github.com/nishant-uxs/krydo)) |
| **Research** | BlockForge — **Accepted**, NetCrypt 2026 |
| **Shipped systems** | 4 live dApps (Ethereum + Stellar) with on-chain deployments |
| **Storage design** | IPFS CIDs on-chain — ~92% on-chain storage reduction ([BlockForge](https://github.com/nishant-uxs/labeval)) |

---

## Projects

Ordered by engineering depth.

### 1. [Krydo](https://github.com/nishant-uxs/krydo) · [Live](https://krydo.onrender.com)
Privacy-preserving credentials on Ethereum. Holders prove predicates (`score ≥ X`) without revealing values — Pedersen commitments + sigma protocols on secp256k1. Hybrid trust: on-chain credential hashes, Firestore query layer, SIWE auth.

### 2. [BlockForge](https://github.com/nishant-uxs/labeval) · [Live](https://blockchain-labeval.onrender.com)
Decentralized lab assessment. OpenZeppelin RBAC contracts, IPFS artifacts, Gemini-assisted grading. NetCrypt 2026 accepted paper.

### 3. [CivicSense](https://github.com/nishant-uxs/CivicSense) · [Live](https://civic-sense-six.vercel.app)
Civic reporting with a 3-step on-chain lifecycle (report → resolve → confirm). Hybrid Supabase / Sepolia storage; Gemini triage for category, severity, duplicates.

### 4. [TrustMesh](https://github.com/nishant-uxs/TrustMesh) · [Live](https://trust-mesh-taupe.vercel.app)
Stellar Soroban trust / reputation network — 6 cooperating contracts, Testnet deployment.

---

## Research

**BlockForge: A Blockchain-Based Decentralized Platform for Transparent Academic Assessment**  
Accepted · 4th International Conference on Networks and Cryptology (**NetCrypt 2026**) · Presentation Oct 2026  
→ [labeval](https://github.com/nishant-uxs/labeval)

---

## Stack

`TypeScript` `Node.js` `Solidity` `Python` · `Ethereum` `Hardhat` `viem`/`ethers` `ZK` `IPFS` `Soroban` · `React` `PostgreSQL` `Firestore` · `GitHub Actions` `Vitest`

---

## Current Focus

- Backend @ Digital South Trust (Crypto Suraksha)
- ZK credential systems (Krydo)
- NetCrypt 2026 presentation
- Upstream contributions to Ethereum / AI developer tooling

---

## Contact

[nishantx.in](https://nishantx.in) · [Resume](./resume.pdf) · [LinkedIn](https://www.linkedin.com/in/nishant-agarwal-62a956322/) · [agarwalnishant812@gmail.com](mailto:agarwalnishant812@gmail.com)

LNMHacks 8.0 Finalist (Top 30) · IIT KGP Tech Triad Top 20
