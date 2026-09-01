# Open Source Contributions

**Merged pull requests only.** Open or closed PRs are listed separately in [README.md](./README.md#open-prs-in-progress).

Contributions are ordered by technical breadth (systems → developer tooling → Web3/AI infra).

---

## Merged

| Repository | PR | Description | Merged |
|------------|-----|-------------|--------|
| [ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) | [#114003](https://github.com/ClickHouse/ClickHouse/pull/114003) | Fixed Keeper `writeAt` cross-segment rewrite: wait for superseded changelog segment removals before acknowledging the rewrite, preventing post-crash `CORRUPTED_DATA` on startup ([issue #112101](https://github.com/ClickHouse/ClickHouse/issues/112101)). Includes `ChangelogTestWriteAtPreviousFile` regression test. | Aug 2026 |
| [NomicFoundation/hardhat](https://github.com/NomicFoundation/hardhat) | [#8464](https://github.com/NomicFoundation/hardhat/pull/8464) | Configuration variables prefer `process.env` over plugin hooks / keystore; unit tests for hook short-circuiting. | Jul 2026 |
| [wevm/viem](https://github.com/wevm/viem) | [#4903](https://github.com/wevm/viem/pull/4903) | ESM `_types` package.json `module` marker for TypeScript NodeNext compatibility. | Jul 2026 |
| [WalletConnect/walletconnect-monorepo](https://github.com/WalletConnect/walletconnect-monorepo) | [#7302](https://github.com/WalletConnect/walletconnect-monorepo/pull/7302) | `EventEmitter` `@types/node` annotations. | Jul 2026 |
| [mastra-ai/mastra](https://github.com/mastra-ai/mastra) | [#20487](https://github.com/mastra-ai/mastra/pull/20487) | Never execute declined tools in agent workflows. | Jul 2026 |
| [mastra-ai/mastra](https://github.com/mastra-ai/mastra) | [#20518](https://github.com/mastra-ai/mastra/pull/20518) | Reuse terminal nested workflow snapshots. | Aug 2026 |
| [hyperlane-xyz/hyperlane-monorepo](https://github.com/hyperlane-xyz/hyperlane-monorepo) | [#9181](https://github.com/hyperlane-xyz/hyperlane-monorepo/pull/9181) | Avoid `HyperlaneMessage::from` panics on malformed multi-chain payloads. | Aug 2026 |
| [FilOzone/pdp](https://github.com/FilOzone/pdp) | [#287](https://github.com/FilOzone/pdp/pull/287) | Emit `PiecesScheduledForRemoval` event. | Aug 2026 |
| [FilOzone/filecoin-services](https://github.com/FilOzone/filecoin-services) | [#566](https://github.com/FilOzone/filecoin-services/pull/566) | PDPVerifier ABI / event wiring (pairs with pdp #287). | Aug 2026 |
| [NomicFoundation/hardhat-website](https://github.com/NomicFoundation/hardhat-website) | [#288](https://github.com/NomicFoundation/hardhat-website/pull/288) | Node.js minimum version documentation → v22.13.0. | Jul 2026 |

---

## Open (in progress)

| Repository | PR | Description | Status |
|------------|-----|-------------|--------|
| [ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) | [#113934](https://github.com/ClickHouse/ClickHouse/pull/113934) | Fix MergeTree MODIFY TTL mutation wedge after crash | Open |
| [dotnet/runtime](https://github.com/dotnet/runtime) | [#132655](https://github.com/dotnet/runtime/pull/132655) | Prevent ThreadPool dispatch from finishing an already-completed Task | Open |
| [NethermindEth/nethermind](https://github.com/NethermindEth/nethermind) | [#12739](https://github.com/NethermindEth/nethermind/pull/12739) | Include beacon tip in `eth_syncing` highest block | Open |
| [OpenZeppelin/openzeppelin-contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) | [#6639](https://github.com/OpenZeppelin/openzeppelin-contracts/pull/6639) | Consistent IERC1967-Upgraded NatSpec in UUPSUpgradeable | Open |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | [#35349](https://github.com/BerriAI/litellm/pull/35349) | Recover partial usage on sync mid-stream failure | Open |

---

## Not merged (do not cite as contributions)

| Repository | PR | Notes |
|------------|-----|-------|
| SciPy/scipy | [#25995](https://github.com/scipy/scipy/pull/25995), [#25996](https://github.com/scipy/scipy/pull/25996) | Closed — not merged |
| nats-io/nats-server | [#8474](https://github.com/nats-io/nats-server/pull/8474) | Not merged |
