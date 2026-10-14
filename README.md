<div align="center">

# KutluhanETH

**Open source contributor · protocol infra · SDK and docs quality**

Small, reviewable changes that land upstream. Correctness first, volume second.

<br/>

![Miden](https://img.shields.io/badge/Miden-7%20merged-1a3a2f?style=flat-square&labelColor=0d1117)
![Arc](https://img.shields.io/badge/Arc-3%20merged-1e3a5f?style=flat-square&labelColor=0d1117)
![Ethereum](https://img.shields.io/badge/Ethereum%20infra-live-2d2a1f?style=flat-square&labelColor=0d1117)
![Solana](https://img.shields.io/badge/Solana%20infra-live-1f2d24?style=flat-square&labelColor=0d1117)

</div>

<br/>

## Upstream merges

### Miden (7)

**[docs #371](https://github.com/0xMiden/docs/pull/371)**  
v0.14 native asset vault key/value encoding (fungible vs NFT, callback flags, leaf semantics)

**[web-sdk #410](https://github.com/0xMiden/web-sdk/pull/410)**  
In-realm `WebClient` freed; replaced IndexedDB handles closed

**[web-sdk #401](https://github.com/0xMiden/web-sdk/pull/401)**  
`buildNetworkNote` exported from both package entries

**[web-sdk #435](https://github.com/0xMiden/web-sdk/pull/435)**  
`length()` exposed on SDK array polyfills for Node

**[miden-vm #3808](https://github.com/0xMiden/miden-vm/pull/3808)**  
Felt `IntValue` Display no longer byte-swaps push immediates

**[miden-vm #3809](https://github.com/0xMiden/miden-vm/pull/3809)**  
`PartialMmr` rejects tracked leaves with incomplete auth paths

**[node #2591](https://github.com/0xMiden/node/pull/2591)**  
Unreachable `InvalidBlockRange::EmptyRange` removed from proto

### Arc (3)

**[arc-node #359](https://github.com/circlefin/arc-node/pull/359)**  
Genesis `ProtocolConfig` aligned with runtime consensus and fee checks

**[arc-node #295](https://github.com/circlefin/arc-node/pull/295)**  
Separated-host RPC transport marked deprecated as of v0.8.0

**[arc-node #307](https://github.com/circlefin/arc-node/pull/307)**  
Stale snapshot URL FIXME removed from execution config defaults

### Ethereum / consensus (2)

**[Lighthouse #10297](https://github.com/sigp/lighthouse/pull/10297)**  
Peer manager RPC protocol match arms grouped

**[Hiero SDK JS #4498](https://github.com/hiero-ledger/hiero-sdk-js/pull/4498)**  
Spelling fixes in entity ID, account, and contract comments

### Tempo and ACK (2)

**[mpp-rs #437](https://github.com/tempoxyz/mpp-rs/pull/437)**  
`FileStore` keys no longer poisoned on partial write

**[ACK #209](https://github.com/agentcommercekit/ack/pull/209)**  
`createDidPkhUri` JSDoc argument order fixed to match the signature

<br/>

## In review

Curated open work across nurture and the broader infra track.

**[Kora #737](https://github.com/solana-foundation/kora/pull/737)**  
`sponsor_only_programs` validation config

**[reth #27857](https://github.com/paradigmxyz/reth/pull/27857)**  
Precompiles shadowed when state override sets code

**[Arc node #372](https://github.com/circlefin/arc-node/pull/372)**  
Effective base-fee floor vs `minBaseFee`

**[ACK #232](https://github.com/agentcommercekit/ack/pull/232)**  
Payment request `expiresAt` enforced

**[Tempo #7930](https://github.com/tempoxyz/tempo/pull/7930)**  
`build-cargo-docs.sh` fails when cargo docs fails

**[Fhenix toolkit #27](https://github.com/FhenixProtocol/fhenix-toolkit/pull/27)**  
Marketplace plugin install pinned to v0.2.0

**[Alloy #274](https://github.com/alloy-rs/examples/pull/274)**  
`eth_sendBundle` MEV example

**[Celestia #2645](https://github.com/celestiaorg/docs/pull/2645)**  
Key `celestia-node` metrics documented

**[Optimism #627](https://github.com/ethereum-optimism/actions/pull/627)**  
Explorer URLs on borrow/swap receipts

**[Fuel #3348](https://github.com/FuelLabs/fuel-core/pull/3348)**  
GraphQL playground auth token / provider query

<br/>

## Focus

1. **Miden:** protocol, web-sdk, docs; testnet builder path
2. **Arc, ACK, Tempo, Fhenix, Thru:** nurture loops and follow-ups
3. **Broader infra:** Foundry, Lighthouse, reth, Kora, Alloy, Celestia, and related stacks

One clear problem per PR. Quality over volume.
