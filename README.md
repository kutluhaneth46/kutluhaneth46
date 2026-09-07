# kutluhaneth46

Contributor across **Arc**, **Tempo**, **Miden**, **Sapiom**, **ACK**, **Base**, **Fhenix**, and **Seismic**: docs, SDK fixes, and small reference repos.

## Showcase repos

| Ecosystem | Project | Link |
|-----------|---------|------|
| **Arc** | Developer Survival Kit (EIP-7825, RPC fallbacks, viem) | [arc-dev-survival-kit](https://github.com/kutluhaneth46/arc-dev-survival-kit) |
| **Tempo** | Batch payout & reconciliation CLI | [tempo-batch-reconcile](https://github.com/kutluhaneth46/tempo-batch-reconcile) |
| **Miden** | Web SDK survival kit (private notes, sync, amounts) | [miden-dev-survival-kit](https://github.com/kutluhaneth46/miden-dev-survival-kit) |
| **Sapiom** | Multi-ecosystem PR & RPC monitor agent | [ecosystem-monitor-agent](https://github.com/kutluhaneth46/ecosystem-monitor-agent) |
| **ACK** | Agent Commerce Kit: pay validation, HITL types, 402 middleware | [agentcommercekit/ack](https://github.com/agentcommercekit/ack/pulls?q=is%3Apr+author%3Akutluhaneth46) |
| **Base** | Receipt Guard (tx/calldata decode + risk before sign) | [receipt-guard](https://github.com/kutluhaneth46/receipt-guard) |
| **Fhenix** | CoFHE survival kit (private counter + sealed bid, Base Sepolia) | [fhenix-cofhe-survival-kit](https://github.com/kutluhaneth46/fhenix-cofhe-survival-kit) |
| **Seismic** | Privacy EVM: anvil access-list hardening, seismic-react docs | [SeismicSystems PRs](https://github.com/pulls?q=is%3Apr+author%3Akutluhaneth46+org%3ASeismicSystems) |

## Community showcases

- Arc: [arc-node #305](https://github.com/circlefin/arc-node/issues/305) · [arc-dev-survival-kit](https://github.com/kutluhaneth46/arc-dev-survival-kit)
- Tempo: [tempo-support #28](https://github.com/tempoxyz/tempo-support/issues/28)
- Miden: [web-sdk #354](https://github.com/0xMiden/web-sdk/issues/354)
- Sapiom: [ecosystem-monitor agent](https://app.sapiom.ai/agents/748)
- ACK: [ack #203](https://github.com/agentcommercekit/ack/pull/203) · [ack #202](https://github.com/agentcommercekit/ack/pull/202)
- Base: [receipt-guard](https://github.com/kutluhaneth46/receipt-guard) · [base/node #1179](https://github.com/base/node/pull/1179)
- Fhenix: [cofhe-hardhat-starter #19](https://github.com/FhenixProtocol/cofhe-hardhat-starter/pull/19) · [fhenix-cofhe-survival-kit](https://github.com/kutluhaneth46/fhenix-cofhe-survival-kit)
- Seismic: [seismic-foundry #227](https://github.com/SeismicSystems/seismic-foundry/pull/227) · [seismic #305](https://github.com/SeismicSystems/seismic/pull/305) · [seismic #306](https://github.com/SeismicSystems/seismic/pull/306)

## Open contributions

<details>
<summary>Arc (circlefin)</summary>

- [arc-node #308](https://github.com/circlefin/arc-node/pull/308) — RPC gascap vs protocol limits
- [arc-node #307](https://github.com/circlefin/arc-node/pull/307) — snapshot URL FIXME cleanup
- [arc-node #306](https://github.com/circlefin/arc-node/pull/306) — operator docs (version pins, eth_blockNumber)
- [arc-commerce #59](https://github.com/circlefin/arc-commerce/pull/59) — admin credentials from env
- [arc-node #299](https://github.com/circlefin/arc-node/pull/299) — public testnet RPC guide (EIP-7825)
- [arc-node #297](https://github.com/circlefin/arc-node/pull/297) — JSON-RPC breaking changes
- [arc-node #295](https://github.com/circlefin/arc-node/pull/295) — RPC transport deprecation
- [arc-commerce #58](https://github.com/circlefin/arc-commerce/pull/58) — reproducible dependency pins

</details>

<details>
<summary>Tempo (tempoxyz)</summary>

- [tempo #7372](https://github.com/tempoxyz/tempo/pull/7372) — faucet empty address validation
- [tempo #7373](https://github.com/tempoxyz/tempo/pull/7373) — signing key file mode 0600

</details>

<details>
<summary>Miden (0xMiden)</summary>

- [web-sdk #356](https://github.com/0xMiden/web-sdk/pull/356) — vite-plugin CI lint
- [web-sdk #355](https://github.com/0xMiden/web-sdk/pull/355) — idxdb downgrade store reset
- [web-sdk #353](https://github.com/0xMiden/web-sdk/pull/353) — sendPrivateNote block hint
- [web-sdk #351](https://github.com/0xMiden/web-sdk/pull/351) — note status fingerprint
- [web-sdk #332](https://github.com/0xMiden/web-sdk/pull/332) — waitForBlock + syncState
- [web-sdk #334](https://github.com/0xMiden/web-sdk/pull/334) — keystore callback bridge
- [guardian-dashboard #49](https://github.com/0xMiden/guardian-dashboard/pull/49) — BigInt amount precision

</details>

<details>
<summary>Sapiom</summary>

- [sapiom-js #748](https://github.com/sapiom/sapiom-js/pull/748) — nullable JSON Schema unions

</details>

<details>
<summary>ACK (agentcommercekit)</summary>

- [ack #203](https://github.com/agentcommercekit/ack/pull/203) — reject empty payment request and option fields
- [ack #202](https://github.com/agentcommercekit/ack/pull/202) — reject negative payment option decimals
- [ack #198](https://github.com/agentcommercekit/ack/pull/198) — accept uppercase 0X prefix in isHexString
- [ack #197](https://github.com/agentcommercekit/ack/pull/197) — cumulative spend budget in policy guard demo
- [ack #195](https://github.com/agentcommercekit/ack/pull/195) — HITL approval request and decision types
- [ack #190](https://github.com/agentcommercekit/ack/pull/190) — HTTP 402 payment-required middleware
- [ack #189](https://github.com/agentcommercekit/ack/pull/189) — map ACK-Pay concepts to MPP and x402

</details>

<details>
<summary>Base</summary>

- [base/node #1179](https://github.com/base/node/pull/1179) — fix remaining broken and outdated docs links
- [base/docs #1931](https://github.com/base/docs/pull/1931) — LICENSE and license badge link
- [base/docs #1929](https://github.com/base/docs/pull/1929) — slashless .mintignore directory globs
- [receipt-guard](https://github.com/kutluhaneth46/receipt-guard) — Base tx/calldata decode + risk receipt
- [base-guild-builder-kit](https://github.com/kutluhaneth46/base-guild-builder-kit) — Guild Builders & Founders deploy kit

</details>


<details>
<summary>Seismic (SeismicSystems)</summary>

- [seismic-foundry #227](https://github.com/SeismicSystems/seismic-foundry/pull/227) — harden eth_createAccessList like eth_call/estimateGas
- [seismic #306](https://github.com/SeismicSystems/seismic/pull/306) — Claude seismic-react template real package APIs
- [seismic #305](https://github.com/SeismicSystems/seismic/pull/305) — SRC20 frontend tutorial seismic-react hooks
- [seismic #293](https://github.com/SeismicSystems/seismic/pull/293) — encode numeric encryption nonces over full 96 bits
- [seismic #291](https://github.com/SeismicSystems/seismic/pull/291) — count ERC-20/SRC-20 transfers toward session spend limit
- [seismic #290](https://github.com/SeismicSystems/seismic/pull/290) — replace broken deploy repo links in TEE network manifest
- [seismic #289](https://github.com/SeismicSystems/seismic/pull/289) — stop trimming AES-GCM precompile output

</details>

<details>
<summary>Fhenix (CoFHE)</summary>

- [cofhe-hardhat-starter #19](https://github.com/FhenixProtocol/cofhe-hardhat-starter/pull/19) — README ACP / sdk 0.7 alignment + `.env.example`
- [fhenix-cofhe-survival-kit](https://github.com/kutluhaneth46/fhenix-cofhe-survival-kit) — private counter + sealed bid demos (mock / Base Sepolia)

</details>

---

*Automated daily status: [ecosystem-monitor](https://app.sapiom.ai/agents/748) (Sapiom agent, Europe/Istanbul 08:00)*
