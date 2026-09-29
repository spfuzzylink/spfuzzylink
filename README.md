<div align="center">

# spfuzzylink

### Build small. Break deliberately. Keep what survives.

**curiosity → code → failure → understanding**

Weekend experiments in storage, distributed systems, and the machinery around AI.

</div>

---

I build things to find out where my assumptions stop working.

A stalled worker. A stale write. A machine that disappears halfway through a task. The interesting part starts when the happy path ends.

My default is a small, inspectable system on hardware I control. Complexity has to earn its place: add a component when an experiment shows why it is needed.

> A useful failure teaches me more than a convincing diagram.

### Current rabbit hole

Extra controls around how AI agents publish to shared storage: scoped access, version checks, retry receipts, and a durable record of what happened.

Starting with Go, SQLite, and ordinary Linux tooling. Exploring Podman and systemd before reaching for a cluster scheduler.

### Things I like to test

- Can a late worker overwrite a newer result?
- Does a retry repeat the effect, or recover the original answer?
- What remains true after a hard restart?
- At what point does another machine actually help?

Small projects. Concrete failure cases. Notes on what held up.

---

<div align="center">

<sub>Built out of curiosity. Shared as experiments.</sub>

</div>
