---
type: Concept
---

A Key-Value (KV) cache in the context of large language models refers to a mechanism for storing and quickly retrieving precomputed information. In Cache-Augmented Generation (CAG), the KV cache encapsulates the inference state of the LLM after processing a set of preloaded documents. This cache allows the model to generate responses based on the preloaded context without needing to retrieve information in real-time during inference. The KV cache is stored on disk or in memory and can be efficiently reset or updated to maintain system performance.