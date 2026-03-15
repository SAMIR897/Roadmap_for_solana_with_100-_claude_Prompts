**Goal:** Master the "Opinionated Framework" that makes Solana development secure and productive.

### Phase 1: The Anatomy of a Program (Week 1-2)
* **Task:** Learn the core macros: #[program], #[derive(Accounts)], and #[account].
* **Claude Instruction:** > "Help me initialize a new Anchor project. Explain what the 8-byte 'Account Discriminator' is and why it's the first thing Anchor checks. Build a 'Counter' dApp with me and show me how to write a TypeScript test for it."

### Phase 2: Security Constraints (Week 3-5)
* **Task:** Mastering constraints like init, mut, signer, and has_one.
* **Claude Instruction:** > "Teach me how to build a 'Vault' where only the owner can withdraw funds. Show me how to use Anchor constraints to prevent an attacker from passing a fake account. We must include custom error codes for every failure."
