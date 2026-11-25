<div align="center">

# KutluhanETH

### Upstream, mid-flight.

I live in the gaps between protocol, SDK, and runtime: the bug that only shows under load, the API that lies about its types, the docs that drift from the binary. I find them, cut a tight PR, and stay until it lands.

**Miden · Arc · Foundry · Wasmtime · Cargo · Lighthouse · Agave**

[kutluhaneth.com](https://kutluhaneth.com) · [X @kutluhaneth](https://x.com/kutluhaneth) · [PRs](https://github.com/pulls?q=author%3Akutluhaneth46)

</div>

---

## Right now

This is the active desk. Not a museum.

| Cooking | What it fixes |
| --- | --- |
| [foundry#18722](https://github.com/foundry-rs/foundry/pull/18722) | Monad reserve policy stays correct across `setEvmVersion` frames |
| [cargo#17802](https://github.com/rust-lang/cargo/pull/17802) | `cargo fix` exits nonzero when applied suggestions break the crate |
| [wasmtime#15459](https://github.com/bytecodealliance/wasmtime/pull/15459) | Expired absolute REALTIME timeouts return ready, not hang |
| [firecracker#6483](https://github.com/firecracker-microvm/firecracker/pull/6483) | aarch64 6.18 guest kernel with 64k pages for CI |
| [agave#17096](https://github.com/anza-xyz/agave/pull/17096) | Websocket URL builder survives port `65535` without panic |
| [lighthouse#10665](https://github.com/sigp/lighthouse/pull/10665) | Password files must be valid UTF-8 before wallet unlock |
| [acapy#4286](https://github.com/openwallet-foundation/acapy/pull/4286) | DIF presentation no longer crashes when `schema` is omitted |
| [cofhe-contracts#197](https://github.com/FhenixProtocol/cofhe-contracts/pull/197) | Conflicting commitment re-posts emit instead of silent swallow |

~37 open upstream. Prefer a few sharp ones over a flood.

---

## Tracks I keep hot

**Miden** is home base. web-sdk workers, note admission, faucet helpers, Felt display, PartialMmr path validation. When the client lies to the browser, I am usually already in the PR.

**Arc** is assign-first, so I wait for the badge, then move fast: genesis protocol config, fee floors, RPC deprecations, denylist CREATE edges.

**EVM + systems** is the wider ring. Foundry cheatcodes and Monad policy, Alloy primitives, Safe addresses, Wasmtime adapters, Firecracker kernels, Cargo CLI behavior, Lighthouse / Agave client edges.

---

## Recently landed

Stuff that already shipped. Short and concrete.

- [miden web-sdk#623](https://github.com/0xMiden/web-sdk/pull/623) / [#624](https://github.com/0xMiden/web-sdk/pull/624) — sync/prove can still read locally; proven batches retry after indeterminate admission
- [miden-vm#3808](https://github.com/0xMiden/miden-vm/pull/3808) / [#3809](https://github.com/0xMiden/miden-vm/pull/3809) — Felt hex display fixed; PartialMmr rejects incomplete tracked paths
- [arc-node#359](https://github.com/circlefin/arc-node/pull/359) — genesis `ProtocolConfig` matches runtime consensus and fee checks
- [cargo#17710](https://github.com/rust-lang/cargo/pull/17710) — OSC 8 terminal links on package names in `cargo info`
- [wasmtime#15197](https://github.com/bytecodealliance/wasmtime/pull/15197) — Cranelift Args/Rets in `Box<[T]>` (less heap churn)
- [foundry#18008](https://github.com/foundry-rs/foundry/pull/18008) — campaign caches isolated; string literals kept in dedup
- [alloy examples#274](https://github.com/alloy-rs/examples/pull/274) — live `eth_sendBundle` MEV path
- [hiero-sdk-js#4809](https://github.com/hiero-ledger/hiero-sdk-js/pull/4809) — deprecated `AccountBalanceQuery` out of coverage noise

---

## How it usually goes

1. Spot a real break (test, repro, or a maintainer thread that went quiet).
2. One problem, one PR. Regression test when it earns its keep.
3. Fix CI myself. Answer review with code, not vibes.
4. On Arc / Hiero-style repos: ask assign first, then open.

If you maintain something in these stacks and have a correctness bug sitting open, drop my handle on the issue. I will take a serious look.
