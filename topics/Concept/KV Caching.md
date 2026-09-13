---
type: Concept
---

An optimization technique used in transformer-based models to speed up inference by storing intermediate key (K) and value (V) states of attention layers during token generation. Instead of recomputing these states for every new token, the model reuses the cached K and V states, reducing redundant calculations and improving efficiency—especially for long sequences. This technique is particularly useful in autoregressive models like large language models (LLMs), where generating each new token depends on all previous tokens. In Cache-Augmented Generation (CAG), the KV cache encapsulates the inference state of the LLM after processing preloaded documents, enabling efficient response generation without real-time retrieval.