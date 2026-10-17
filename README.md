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

### ☕ Currently building: **Questlock**

![Questlock — lower cost per accepted task, including human rework](assets/questlock-brand.svg)

You already paid for the answer. Why generate it again to change a sentence?

**[Questlock](https://github.com/spfuzzylink/questlock)** reuses completed work,
applies checked literal edits without a model, and delegates bounded tasks to
local or configured models. Go + SQLite, small enough to inspect.

**OpenRouter routes the model. Questlock coordinates the work.** An independent
companion for the OpenRouter ecosystem, with shared task admission, reusable
results and explicit human feedback. Credit to OpenRouter, SGLang and Langfuse
for the layers they provide.

**Experimental v0.7.0** makes the first step easier:

- Choose Codex, Claude Code or Claude Desktop with `questlock setup`.
- Finish a checked first task with zero model calls.
- Use `doctor` and guarded config recovery instead of guessing at settings.
- Run the main Codex CLI loop locally with an installed Ollama model.

Local work has no provider token bill. The surrounding hosted chat still uses
its normal allowance. The goal is less paid repetition, with quality and human
rework counted; the [build report](https://github.com/spfuzzylink/questlock/blob/main/docs/success-report-v0.7.0.md)
keeps the failures visible too.

[Get started](https://github.com/spfuzzylink/questlock/blob/main/docs/onboarding.md) ·
[Downloads](https://github.com/spfuzzylink/questlock/releases/tag/v0.7.0) ·
[Architecture](https://github.com/spfuzzylink/questlock/blob/main/docs/architecture.md) ·
[Container](https://github.com/spfuzzylink/questlock/pkgs/container/questlock) ·
[Fork it](https://github.com/spfuzzylink/questlock/fork)

---

<div align="center">

<sub>Curiosity starts the experiment. Evidence decides what stays.</sub>

</div>
