---
type: Concept
---

Positional encoding is a technique used to inject information about the relative or absolute positions of tokens in a sequence into the model. Since the Transformer model does not use recurrence or convolution, positional encoding is crucial for the model to understand the order of the sequence. In the Transformer, positional encodings are added to the input embeddings at the bottom of the encoder and decoder stacks. These encodings are typically based on sine and cosine functions of different frequencies, allowing the model to easily learn to attend by relative positions. Positional encoding helps the model to maintain the sequential nature of the data and improve its performance on tasks that require understanding the order of elements in the sequence.