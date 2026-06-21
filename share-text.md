# Share text

## X / Twitter

new essay: The Stochastic CPU.

the cloud is being rebuilt for AI agents. the LLM is a non-deterministic CPU — every layer above it has to change.

>1000× cheaper inference. 14% → 95% on SWE-bench in 27 months.

https://zozo123.github.io/stochastic-cpu/

---

## LinkedIn

I wrote a field report on what's actually happening underneath the AI agent wave.

The thesis: the LLM is the new CPU — and for the first time, the CPU is stochastic. f(x) ≠ y. Same input, different output. The entire stack we built for determinism does not survive contact.

Three things changed faster than anyone modeled:

1. Inference got more than 1000× cheaper in three years.
2. SWE-bench went from 14% to 95% in 27 months.
3. The runtime, the IDE, and the cloud are being rewritten around this.

Read it: https://zozo123.github.io/stochastic-cpu/

---

## Hacker News

**Title:**

The Stochastic CPU – a field report on the cloud being rebuilt for AI agents

**Top comment:**

Author here. The core claim: the LLM is a CPU whose output isn't a function of its input — f(x) ≠ y — and that single property breaks the determinism assumption every layer of our cloud was built on. Curious where HN thinks the analogy holds and where it breaks.
