---
type: Concept
---

Rotary Position Embeddings (RoPE) is a technique used in transformer models to incorporate positional information into the embeddings. It applies sinusoidal functions to the embeddings to encode positional information, which helps the model understand the order of tokens in a sequence. RoPE is particularly useful in improving the throughput of transformer models by applying the embeddings to a portion of the head embedding dimensions.