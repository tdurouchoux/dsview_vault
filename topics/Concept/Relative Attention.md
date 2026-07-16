---
type: Concept
---

Relative attention is an alternative to traditional positional encoding methods like Rotary Position Embedding (RoPE) in transformer models. Instead of injecting positional information into the key and query vectors, relative attention directly learns position information within the attention logits. In Inkling, each attention layer includes a fourth projection that produces a per-token, per-head relative feature. This feature is then adjusted using distance information between the key and query vectors, enhancing the model's ability to capture positional relationships in the input data.