# KutluhanETH

Open source contributor focused on Miden, Arc, ACK, Tempo, and Ethereum / Solana infra.

Docs, protocol correctness, and SDK quality. Small clear changes that land upstream.

## Upstream merges

### Miden (7)

<a href="https://github.com/0xMiden/docs/pull/371">Miden docs #371</a>
v0.14 native asset vault key/value encoding documented (fungible vs NFT, callback flags, leaf semantics).

<a href="https://github.com/0xMiden/web-sdk/pull/410">Miden web-sdk #410</a>
In-realm WebClient freed and replaced IndexedDB handles closed.

<a href="https://github.com/0xMiden/web-sdk/pull/401">Miden web-sdk #401</a>
`buildNetworkNote` exported from both package entries.

<a href="https://github.com/0xMiden/web-sdk/pull/435">Miden web-sdk #435</a>
`length()` exposed on SDK array polyfills for Node.

<a href="https://github.com/0xMiden/miden-vm/pull/3808">Miden VM #3808</a>
Felt IntValue Display no longer byte swaps push immediates.

<a href="https://github.com/0xMiden/miden-vm/pull/3809">Miden VM #3809</a>
PartialMmr rejects tracked leaves with incomplete authentication paths.

<a href="https://github.com/0xMiden/node/pull/2591">Miden node #2591</a>
Unreachable `InvalidBlockRange::EmptyRange` path removed from proto.

### Arc

<a href="https://github.com/circlefin/arc-node/pull/359">Arc node #359</a>
Genesis ProtocolConfig aligned with runtime consensus and fee checks.

<a href="https://github.com/circlefin/arc-node/pull/295">Arc node #295</a>
Separated host RPC transport marked deprecated as of v0.8.0.

<a href="https://github.com/circlefin/arc-node/pull/307">Arc node #307</a>
Stale snapshot URL FIXME removed from execution config defaults.

### Tempo

<a href="https://github.com/tempoxyz/mpp-rs/pull/437">Tempo mpp-rs #437</a>
FileStore keys no longer poisoned on partial write.

### ACK

<a href="https://github.com/agentcommercekit/ack/pull/209">ACK #209</a>
`createDidPkhUri` JSDoc argument order fixed to match the real signature.

## Selected open work

<a href="https://github.com/solana-foundation/kora/pull/737">Kora #737</a>
`sponsor_only_programs` validation config.

<a href="https://github.com/hiero-ledger/hiero-sdk-js/pull/4498">Hiero SDK JS #4498</a>
Spelling fixes in entity ID, account, and contract comments.

<a href="https://github.com/sigp/lighthouse/pull/10297">Lighthouse #10297</a>
Peer manager RPC protocol match arms grouped.

<a href="https://github.com/paradigmxyz/reth/pull/27857">reth #27857</a>
Precompiles shadowed when state override sets code.

<a href="https://github.com/circlefin/arc-node/pull/372">Arc node #372</a>
Effective base fee floor documented against `minBaseFee`.

<a href="https://github.com/agentcommercekit/ack/pull/232">ACK #232</a>
Payment request `expiresAt` enforced.

<a href="https://github.com/tempoxyz/tempo/pull/7930">Tempo #7930</a>
`build-cargo-docs.sh` fails when cargo docs fails.

<a href="https://github.com/FhenixProtocol/fhenix-toolkit/pull/27">Fhenix toolkit #27</a>
Marketplace plugin install pinned to the v0.2.0 tag and commit.

## Focus

1. Miden — protocol, web-sdk, docs; testnet builder path
2. Arc / ACK / Tempo nurture
3. Broader infra track — Foundry, Lighthouse, reth, Kora, Alloy, Celestia, and related stacks

Quality over volume. One clear problem per PR.
