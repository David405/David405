Senior Blockchain Infrastructure Engineer. 8 years building across smart contract protocol engineering, blockchain infrastructure, and distributed backend systems. I build across all three layers of the stack.

I build systems that stay correct through retries, inconsistent providers, and partial failure.

Building [AfroPanda Esports](https://afropandaesports.com), leading engineering @ [PandaPay Africa](https://pandapay.africa/).

---

### A few things I've shipped

- Owned the intents-based cross-swap backend at [TAO.com](https://tao.com) — solver integration, fee calculation, pricing, and settlement flows across EVM networks and Bittensor.

- Designed a separate Bittensor Order Service and Matcher at TAO.com — signed order registration, idempotent requests, and execution isolated from the public API.

- Designed the backend infrastructure at [Bloom](https://bloom.social) — token management, portfolio aggregation, real-time notifications, and cross-chain transaction parsing where external indexers fall short.

- Architected Baki Exchange at [Canza Finance](https://canza.finance) — Solidity collateral vaults, Pyth oracle integrations, liquidations, and swap execution.

- Built Bittensor liquidity vaults and production keeper infrastructure through [General Tensor](https://generaltensor.io) — ERC-4626 vaults, EIP-712 lock controls, and scan → verify → execute → confirm pipelines with PostgreSQL audit trails.
---

### What I'm building

**[FlatMerkle](https://github.com/David405/flatmerkle)**

Benchmarking contiguous Vec-based vs pointer-based Merkle tree layouts in Rust. Hypotheses locked before implementation. Results published regardless of outcome.

[Read the write-up →](https://davidasamonye.com/research/flatmerkle-paper)

**[keeper-rs](https://github.com/David405/keeper-rs)**

Keepers are off-chain bots that monitor on-chain state and trigger contract executions — liquidations, settlements, order fills. Most protocol teams build one from scratch and couple it tightly to their contract.

Define a strategy trait, plug in your contract logic, and the engine handles the rest — scan, verify, execute, confirm, retry on failure, dead-letter on persistent failure, emit metrics throughout. Coming soon.

---

[davidasamonye.com](https://davidasamonye.com) · [Twitter](https://twitter.com/david_asamonye) · [LinkedIn](https://linkedin.com/in/davidasamonye)
