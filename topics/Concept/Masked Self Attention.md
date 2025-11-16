---
type: Concept
---

A variant of self-attention used in the decoder of the Transformer architecture. Masked self-attention prevents the model from attending to future tokens when predicting the next word, ensuring that the model generates text in a left-to-right manner. This is achieved by applying a look-ahead mask to the attention scores, setting future positions to negative infinity before applying the softmax function. Masked attention is crucial for autoregressive tasks like language modeling, where the model should only have access to previous tokens when predicting the next token. The mask is typically implemented as a binary matrix that zeros out attention scores corresponding to future positions, effectively preventing the model from "cheating" by looking ahead in the sequence.