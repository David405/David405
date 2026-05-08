Senior Blockchain Infrastructure Engineer. 8 years building across smart
contract protocol engineering, blockchain infrastructure, and distributed
backend systems. I build across all three layers of the stack.

Co-founder of AfroPanda Esports
(afropandaesports.com), leading engineering including PandaPay.


A few things I've shipped

· Architected Baki Exchange at Canza Finance — Solidity vaults, Pyth oracle
  integrations, liquidation mechanics.

· Built the cross-chain transaction parsing engine at Bloom — protocol adapter
  registry handling Relay and MetaMask bridge flows where standard indexers fail.

· Built production keeper infrastructure at 0xMarkets — atomic
  scan→verify→execute→confirm pipelines with PostgreSQL-backed audit trails.

· Reduced API response latency 60–85% via Redis-backed caching across background workers and job pipelines at Bloom.


What I'm building

FlatMerkle (github.com/David405/flatmerkle)
Benchmarking contiguous Vec-based vs pointer-based Merkle tree layouts in Rust.
Hypotheses locked before implementation. Results published regardless of outcome.
davidasamonye.com/research/flatmerkle-paper

keeper-rs (github.com/David405/keeper-rs)
Keepers are off-chain bots that monitor on-chain state and trigger contract
executions — liquidations, settlements, order fills. Most protocol teams
build one from scratch and couple it tightly to their contract.

keeper-rs is a generalised engine extracted from production use across two
protocols: Baki (synthetic assets, Canza Finance) and 0xMarkets (perpetuals).
Define a strategy trait, plug in your contract logic, and the engine handles
the rest — scan, verify, execute, confirm, retry on failure, dead-letter on
persistent failure, emit metrics throughout. Coming soon.


davidasamonye.com · twitter.com/david_asamonye · linkedin.com/in/davidasamonye
