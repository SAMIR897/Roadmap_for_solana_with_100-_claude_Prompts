## Roadmap 2: The Solana Ecosystem (Core SVM)

**Goal:** Understand how Solana treats the blockchain as a high-performance, parallel computer.
### Phase 1: Accounts & State (Week 1-2)
* **Concept:** Solana is a stateless machine. Programs are like "Functions" and Accounts are like "Files" on a hard drive.
* **Claude Instruction:** > "Explain why Solana can run transactions in parallel while Ethereum cannot. Guide me through using the Solana CLI to create a wallet, request airdrops on Devnet, and inspect the raw data stored in an account."

### Phase 2: PDAs & Transactions (Week 3-4)
* **Concept:** Program Derived Addresses (PDAs) are accounts that only a specific program can "sign" for.
* **Claude Instruction:** > "Teach me the secret of PDAs. How do seeds and bumps work? Help me write a native Rust program that allows a user to store their 'High Score' in a PDA-derived account. Explain why this account doesn't have a private key."
