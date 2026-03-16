# Module 3: Anchor Framework Mastery (100 Prompts)

## 3.1 The Anchor Workflow (1-25)

1. "Why use Anchor? Explain the phrase 'Opinionated and Powerful'."
2. "What does `anchor init` do? Explain the project file structure."
3. "Explain `Anchor.toml`. What are 'Providers' and 'Scripts'?"
4. "What is the `#[program]` macro? How does it simplify entry points?"
5. "Explain `declare_id!`. Why must it match my public key?"
6. "What is the `Context<T>` struct? What fields does it give me?"
7. "Explain `#[derive(Accounts)]`. How does it automate validation?"
8. "What is an 'IDL' (Interface Description Language)?"
9. "How does Anchor generate a TypeScript client from my Rust code?"
10. "Explain the 8-byte 'Account Discriminator'. Why is it used for safety?"
11. "What is the `Account<'info, T>` type? What checks does it perform?"
12. "Explain `Signer<'info>`. How is it different from a regular account?"
13. "What is `SystemAccount<'info>`? When should I use it?"
14. "Explain `Program<'info, T>`. How do I validate an executable?"
15. "How do I use `anchor build`? What are the output files?"
16. "What does `anchor test` do? How does it spin up a local validator?"
17. "Explain `anchor deploy`. How do I point it to Devnet?"
18. "What is `anchor keys sync`? Why is it useful for team projects?"
19. "Explain `anchor verify`. How does it prove my source code matches the chain?"
20. "What is the `workspace` object in Anchor tests?"
21. "Explain `anchor expand`. How can I see the 'magic' code Anchor writes for me?"
22. "What is AVM (Anchor Version Manager)?"
23. "Explain the `prelude` module. What imports are included by default?"
24. "How do I add a new instruction to my Anchor program?"
25. "Explain 'Remaining Accounts'. How do I pass a dynamic list of accounts?"

## 3.2 Constraints & Validation (26-50)

26. "What is the `#[account(..)]` attribute? Why is it the heart of Anchor?"
27. "Explain the `init` constraint. What are the 3 things it does?"
28. "What is the `payer` constraint? Who pays for account creation?"
29. "Explain the `space` constraint. How do I calculate 8 + size of my struct?"
30. "What is the `mut` (mutable) constraint? What happens
