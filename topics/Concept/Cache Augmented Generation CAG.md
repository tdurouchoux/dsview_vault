---
type: Concept
---

Cache-Augmented Generation (CAG) is an alternative approach to Retrieval-Augmented Generation (RAG) that leverages the extended context capabilities of large language models (LLMs). Instead of relying on real-time retrieval, CAG preloads all relevant documents and precomputes the key-value (KV) cache, which encapsulates the inference state of the LLM. During inference, the model uses these preloaded parameters to answer queries without additional retrieval steps, eliminating retrieval latency and minimizing retrieval errors.