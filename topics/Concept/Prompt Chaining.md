---
type: Concept
---

Prompt chaining is a workflow that decomposes a task into a sequence of steps, where each LLM call processes the output of the previous one. This method is used to trade off latency for higher accuracy by making each LLM call an easier task. It is particularly useful for tasks that can be easily and cleanly decomposed into fixed subtasks.