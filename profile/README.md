# JMDT: The Truth Layer 

Jupiter Meta Data Token (JMDT) is the native utility token of the Truth Layer, Jupiter Meta Labs’ decentralized data and identity infrastructure for enterprise applications that need trusted, privacy-preserving records. JMDT powers the ecosystem’s applications, including SuperJ, Hercules and Poseidon, which together serve over 20 million users and more than 40 enterprise customers. The token is used for transaction fees, network validation, settlement and decentralized identity across the Truth Layer.

The network is an Ethereum-connected Layer 2. JMDT nodes execute EVM-compatible transactions and produce blocks on demand: a block is created only when there are transactions to process, so no resources are spent on empty blocks. Batches of blocks are proven with zero-knowledge STARK proofs from Auspex, Jupiter Meta’s in-house prover, which relies on hash-based cryptography rather than elliptic curves. Each batch is attested by a validator committee and anchored to Ethereum Layer 1 through a settlement contract that links every batch to the one before it. A Layer 3 Directed Acyclic Graph (DAG) for fast, localized enterprise workloads is in development.

Blocks are validated with Asynchronous Validation Consensus (AVC). For each block, a committee is drawn at random from the registered validators, using randomness the network generates itself (RANDAO combined with a verifiable delay function), so no party can choose who validates. Committee members check the block and sign their votes with BLS signatures bound to that exact block, chain and height. A block is final only with a certificate from at least two-thirds of its committee, compressed into a single aggregate signature. The certificate covers the block’s transactions, its place in the chain, its timestamp and where its fees are paid, so a finalized block cannot be altered without invalidating it. Conflicting blocks at the same height are detected and recorded, and nodes joining the network verify these certificates as they sync.

Finalized blocks are written to an append-only ledger with signed checkpoints, giving enterprises transparent, tamper-evident and auditable records.

JMDT is hard-capped at 1 billion tokens, with a current circulating supply of 250 million tokens.

Privacy and compliance are foundational to the Truth Layer. The ecosystem supports decentralized identifiers (DIDs) tied to users’ own keys, so identity can be proven without placing personally identifiable information (PII) on-chain. This privacy-preserving architecture is designed to support regulatory frameworks including GDPR, DPDPA and HIPAA.

Join us in building the next generation of decentralized, privacy-first applications with JMDT.
