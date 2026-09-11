# KutluhanETH

Open source contributor focused on Arc, Miden, and ACK.

Docs, protocol correctness, and SDK quality. Small clear changes that land upstream.

## Upstream merges

### Arc

<a href="https://github.com/circlefin/arc-node/pull/359">Arc node #359</a>
Genesis ProtocolConfig aligned with runtime consensus and fee checks.

<a href="https://github.com/circlefin/arc-node/pull/295">Arc node #295</a>
Separated host RPC transport marked deprecated as of v0.8.0.

<a href="https://github.com/circlefin/arc-node/pull/307">Arc node #307</a>
Stale snapshot URL FIXME removed from execution config defaults.

### Miden

<a href="https://github.com/0xMiden/miden-vm/pull/3809">Miden VM #3809</a>
PartialMmr from_parts and deserialization reject tracked leaves with incomplete authentication paths.

<a href="https://github.com/0xMiden/node/pull/2591">Miden node #2591</a>
Unreachable InvalidBlockRange EmptyRange path removed from proto.

### ACK

<a href="https://github.com/agentcommercekit/ack/pull/209">ACK #209</a>
createDidPkhUri JSDoc argument order fixed to match the real signature.

## Selected open work

<a href="https://github.com/circlefin/arc-node/pull/372">Arc node #372</a>
Effective base fee floor documented against minBaseFee.

<a href="https://github.com/circlefin/arc-node/pull/373">Arc node #373</a>
Public testnet RPC capability notes for follow sync and app clients.

<a href="https://github.com/0xMiden/miden-vm/pull/3808">Miden VM #3808</a>
Felt IntValue Display no longer byte swaps push immediates.

<a href="https://github.com/agentcommercekit/ack/pull/212">ACK #212</a>
Invalid new BigInt usage fixed in the ack pay README example.

<a href="https://github.com/FhenixProtocol/fhenix-toolkit/pull/27">Fhenix toolkit #27</a>
Marketplace plugin install pinned to the v0.2.0 tag and commit.

## Focus

1. Arc node and operator docs
2. Miden assigned fixes and review threads
3. ACK only when the topic is free of prior PRs

Quality over volume. One clear problem per PR.
