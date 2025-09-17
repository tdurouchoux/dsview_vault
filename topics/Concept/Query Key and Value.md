---
type: Concept
---

In the attention mechanism, queries, keys, and values are vectors derived from the input embeddings through linear transformations. Queries represent the current token's context, keys represent the context of other tokens, and values contain the actual information to be combined. The attention scores are computed as the dot products between queries and keys, which are then used to weight the values, enabling the model to focus on relevant parts of the input sequence.