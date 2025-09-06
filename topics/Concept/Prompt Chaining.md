---
type: Concept
---

Prompt chaining is a workflow pattern where a task is decomposed into a sequence of steps, with each LLM call processing the output of the previous one. This approach is used to trade off latency for higher accuracy by breaking down complex tasks into simpler, manageable subtasks. Programmatic checks can be added at intermediate steps to ensure the process remains on track.