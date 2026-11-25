# KutluhanETH

Protocol and tooling contributor. Most of my work is upstream: correctness fixes, SDK surface, runtime edge cases, and the docs that keep those changes usable.

Deepest time goes into **Miden**, **Arc**, and adjacent Ethereum / Solana infra. Same approach everywhere: isolate a real failure mode, ship a small PR a maintainer can review in one pass, then stay through CI and review.

[kutluhaneth.com](https://kutluhaneth.com) · [X](https://x.com/kutluhaneth) · [GitHub](https://github.com/kutluhaneth46)

## Surfaces

- **Miden** — web-sdk, VM, node, docs: client lifecycle, note and account paths, WASM workers
- **Arc** — `arc-node` genesis, fees, RPC, contribution-gated protocol bugs
- **EVM tooling** — Foundry, Alloy, Safe SDK, ACA-Py credential and presentation edge cases
- **Runtime / systems** — Wasmtime, Firecracker guest kernels, Cargo CLI
- **Clients / L1** — Lighthouse, Agave, Celestia docs, Hiero SDK

## Selected merges

**Miden**
- [web-sdk#623](https://github.com/0xMiden/web-sdk/pull/623) — local reads during worker sync and prove
- [web-sdk#624](https://github.com/0xMiden/web-sdk/pull/624) — retry proven batches after indeterminate admission
- [miden-vm#3808](https://github.com/0xMiden/miden-vm/pull/3808) — Felt `Display` no longer byte-swaps push immediates
- [miden-vm#3809](https://github.com/0xMiden/miden-vm/pull/3809) — `PartialMmr` rejects tracked leaves with incomplete auth paths

**Arc**
- [arc-node#359](https://github.com/circlefin/arc-node/pull/359) — genesis `ProtocolConfig` aligned with runtime consensus and fee checks
- [arc-node#295](https://github.com/circlefin/arc-node/pull/295) — separated-host RPC transport deprecated as of v0.8.0

**Infra**
- [cargo#17710](https://github.com/rust-lang/cargo/pull/17710) — OSC 8 links for package names in `cargo info`
- [wasmtime#15197](https://github.com/bytecodealliance/wasmtime/pull/15197) — Cranelift `Args` / `Rets` in `Box<[T]>` instead of `Vec`
- [foundry#18008](https://github.com/foundry-rs/foundry/pull/18008) — isolate campaign caches; keep string literals in dedup
- [firecracker#6404](https://github.com/firecracker-microvm/firecracker/pull/6404) — MultiNamePath 255-segment AML limit documented
- [alloy examples#274](https://github.com/alloy-rs/examples/pull/274) — `eth_sendBundle` MEV example
- [lighthouse#10297](https://github.com/sigp/lighthouse/pull/10297) — peer manager RPC protocol match arms grouped

## In flight

- [foundry#18722](https://github.com/foundry-rs/foundry/pull/18722) — Monad reserve policy refresh on `setEvmVersion` frames
- [cargo#17802](https://github.com/rust-lang/cargo/pull/17802) — nonzero exit when applied `cargo fix` suggestions fail verification
- [wasmtime#15459](https://github.com/bytecodealliance/wasmtime/pull/15459) — expired absolute REALTIME timeout returns ready
- [firecracker#6483](https://github.com/firecracker-microvm/firecracker/pull/6483) — aarch64 6.18 64k-page CI guest kernel config
- [agave#17096](https://github.com/anza-xyz/agave/pull/17096) — websocket URL builder no longer panics on port 65535
