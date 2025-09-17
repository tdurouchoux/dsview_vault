---
type: Concept
---

Unpadding and Sequence Packing are techniques used in ModernBERT to enhance computational efficiency. Unpadding removes padding tokens from sequences, avoiding wasted computation on non-semantic tokens. Sequence Packing concatenates individual sequences into mini-batches, maximizing computational efficiency by grouping sequences close to the model's maximum input length. These techniques, combined with Flash Attention, result in significant speedups, making ModernBERT more efficient, especially for long context inputs.