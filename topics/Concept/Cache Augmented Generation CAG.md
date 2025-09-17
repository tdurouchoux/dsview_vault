---
type: Concept
---

Cache-Augmented Generation (CAG) is a novel approach proposed as an alternative to Retrieval-Augmented Generation (RAG). It leverages the extended context capabilities of large language models (LLMs) to preload relevant documents and precompute key-value (KV) caches. During inference, the model uses these preloaded parameters to answer queries without the need for real-time retrieval, thereby eliminating retrieval latency and minimizing retrieval errors. CAG aims to provide a streamlined and efficient alternative to RAG, particularly for tasks with a constrained and manageable knowledge base.