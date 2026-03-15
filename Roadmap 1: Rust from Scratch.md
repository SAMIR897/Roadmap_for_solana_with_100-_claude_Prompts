# Roadmap 1: Rust from Scratch (The "CS50" Professor Path)

**Goal:** Transition from a total novice to a systems engineer using Claude as your high-energy personal tutor.

### Phase 1: The Binary World & Scalar Types (Week 1)
* **Mental Model:** Imagine the computer as a series of light bulbs that can only be "On" or "Off".
* **Task:** Master variables, mutability, and basic math.
* **Claude Instruction:** > "Act as a high-energy Harvard CS Professor. Use metaphors like light bulbs and phone books to teach me the absolute basics of Rust syntax. Start with the difference between i32 and f64. For every lesson, give me one 'Broken Code' snippet that I must fix before we move on."

### Phase 2: The Physicality of Memory (Week 2-3)
* **Mental Model:** Memory in Rust is like a physical object—a book or a dollar bill. If I give it to you, I no longer have it. This is "Ownership".
* **Task:** Ownership, Borrowing, and the Stack vs. Heap.
* **Claude Instruction:** > "Professor, explain the Ownership rules using the analogy of a 'View-Only' Google Doc versus an 'Editor' role. Help me build a 'Bouncer' program that checks a whitelist and teach me why the compiler screams when I try to use a variable after it's been 'moved'."

### Phase 3: The Toolbox (Week 4-6)
* **Mental Model:** Traits are like interfaces for tools. If a tool "implements" the Hammer trait, I know I can hit() things with it regardless of what the tool is made of.
* **Task:** Structs, Enums, Traits, and Pattern Matching.
* **Claude Instruction:** > "Guide me in building a CLI Task Manager. Teach me how Enums act like a 'Multiple Choice' question for the computer, and how the match keyword forces me to handle every possible answer. Show me how to use Option to handle the 'Billion Dollar Mistake' of null pointers."
