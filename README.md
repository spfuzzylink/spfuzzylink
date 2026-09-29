<div align="center">

# spfuzzylink

### Every abstraction is a hypothesis.

**Build something small enough to understand. Then ask it a difficult question.**

curiosity → experiment → failure → understanding

</div>

---

I’m interested in the distance between a system that works and a system whose failure I can explain.

Some questions only become clear after you build the thing. Give it a little state, a little concurrency, and an inconvenient restart. See which assumptions survive.

I like starting with the fewest moving parts I can get away with. Complexity has to earn its place. A new component should explain more than it hides.

> The most useful thing a side project can produce is a better question.

Most repositories here begin as a curiosity. Some may become useful tools. Each should leave behind a clearer understanding of how something behaves when the happy path ends.

### A few principles I keep coming back to

- Make the state visible.
- Treat failure as something to study.
- Understand the small system before growing it.
- Let evidence change the design.
- Leave enough notes for the next curious person.

---

### ☕ Brewing / loading…

**Agent Fence** — a small experiment in how AI agents share state without silently overwriting one another’s work.

The questions taking shape:

- What authority should a late worker still have?
- What does it mean to retry a write after the answer was lost?
- Which promises survive a process restart?
- How far can one self-hosted machine take this?

Go, SQLite, and ordinary Linux tooling are the starting ingredients. Podman and systemd are part of the experiment. Kubernetes stays outside the first sketch.

Small enough to inspect. Interesting enough to break on purpose.

---

<div align="center">

<sub>Curiosity starts the experiment. Evidence decides what stays.</sub>

</div>
