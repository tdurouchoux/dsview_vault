---
type: Concept
---

Self-attention, also known as scaled dot-product attention or intra-attention, is a core component of the Transformer architecture. It allows the model to weigh the importance of input elements with respect to each other, regardless of their distance in the sequence. This mechanism computes attention scores by taking dot products of query, key, and value vectors derived from the input embeddings. These scores are then used to create a weighted sum of the values, effectively enabling the model to focus on different parts of the input sequence when producing each output element. Self-attention contributes to the model's ability to handle long-range dependencies and parallelize computations effectively.