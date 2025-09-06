---
type: Concept
---

Masked attention is a technique used in the decoder part of the Transformer to prevent the model from attending to future positions in the sequence during training. This is crucial for autoregressive tasks where the model generates the output sequence one token at a time. The mask is typically implemented as a binary matrix that zeros out attention scores for future positions, ensuring that the model can only attend to previous tokens.