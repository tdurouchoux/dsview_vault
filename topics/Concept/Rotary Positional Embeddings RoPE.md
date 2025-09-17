---
type: Concept
---

Rotary Positional Embeddings (RoPE) is a technique used in ModernBERT and transformer models to improve the model's understanding of the relative positions of words in a sequence. Unlike traditional positional encodings, RoPE allows the model to better capture the contextual relationships between tokens, enabling it to handle longer sequence lengths more effectively. This method is inspired by advancements in transformer architectures and contributes to the model's ability to process and understand long-context inputs efficiently. It applies rotary matrices to the input embeddings, allowing the model to better capture positional information and improve throughput, particularly useful for tasks involving long sequences of data.