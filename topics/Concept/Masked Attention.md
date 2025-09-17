---
type: Concept
---

Masked attention is a technique used in the decoder part of the Transformer to prevent the model from attending to future positions in the sequence during training. This is crucial for autoregressive tasks like language modeling, where the model should only have access to previous tokens when predicting the next token. The mask is typically implemented as a binary matrix that zeros out attention scores corresponding to future positions, effectively preventing the model from "cheating" by looking ahead in the sequence.