---
type: Library
---

A Read-Eval-Print Loop environment, typically implemented as a Python REPL notebook (e.g., Jupyter), used in Recursive Language Models (RLMs) to store and interact with context. The REPL environment allows the root language model to programmatically peek at, partition, transform, and map over the input context, as well as launch recursive sub-queries. This environment provides flexibility and control over context processing, enabling RLMs to avoid clogging the root model's context window and to scale to near-infinite context lengths.