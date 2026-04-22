---
already_read: false
link: https://raw.works/rlms-are-the-new-reasoning-models/
read_priority: 5
relevance: 0
source: hugging face
tags:
- Large_Language_Model
type: Content
upload_date: '2026-04-22'
---

https://raw.works/rlms-are-the-new-reasoning-models/
## Summary

RLMs (Recursive Language Models) are a new inference paradigm where models treat their input prompt as an environment to inspect, slice, and recursively query, collapsing reasoning and tool use into a single abstraction. They outperform traditional models on long-context tasks (e.g., Oolong, LongMemEval) and long-horizon reasoning (LongCoT). Key challenges include cost, time, and models' inherent difficulty with recursive behavior. Post-training models in RLM harnesses and leveraging smaller models on consumer hardware are promising next steps. Reference implementations like `rlm`, `dspy.RLM`, and `ax-llm/ax` facilitate experimentation.
## Links

- [Recursive Language Models (arXiv, Dec. 2025; revised Jan. 2026)](https://arxiv.org/abs/2512.24601) : This paper formalizes Recursive Language Models (RLMs) as a general inference paradigm, explaining how they treat prompts as external environments and enable recursive subcalls for improved reasoning and tool use.
- [LongCoT: Benchmarking Long-Horizon Chain-of-Thought Reasoning](https://arxiv.org/abs/2604.14140) : This paper introduces LongCoT, a benchmark designed to evaluate long-horizon chain-of-thought reasoning, providing a standardized way to measure progress in this challenging area.
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) : This foundational paper introduces the ReAct framework, which integrates reasoning and tool use in language models, paving the way for RLMs.
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) : This paper explores how language models can autonomously learn to use tools, a key capability for RLMs.
- [The Mismanaged Geniuses Hypothesis](https://alexzhang13.github.io/blog/2026/mgh/) : This blog post reframes the evolution of reasoning models, arguing that RLMs represent a more expressive scaffold for managing executable external computation.

## Topics

![[topics/Concept/Recursive Language Models RLMs]]

![[topics/Concept/Long Context Reasoning]]

![[topics/Concept/Memory Systems in LLMs]]

![[topics/Concept/Long Horizon Chain of Thought LongCoT]]

![[topics/Concept/Inference Time Compute Scaling]]

![[topics/Concept/Task Decomposition]]

![[topics/Platform/Oolong]]

![[topics/Concept/Uncertainty Aware Program Search]]

![[topics/Concept/Agentic Tool Use]]

![[topics/Library/DSPy]]