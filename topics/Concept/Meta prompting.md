---
type: Concept
---

Meta-prompting is an instruction-tuning approach where an LLM analyzes and improves prompts based on inputs, outputs, reference outputs, and current prompt scores. This process is repeated in mini-batches, with the best-performing prompt on a development set being retained. It is effective for discovering rules or preferences in the data that may not be within the LLM's domain knowledge.