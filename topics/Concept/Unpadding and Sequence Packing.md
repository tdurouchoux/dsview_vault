---
type: Concept
---

Unpadding and Sequence Packing are techniques used to enhance the efficiency of encoder models like ModernBERT. Unpadding removes unnecessary padding tokens, allowing for more efficient computation by avoiding wasted resources on non-informative tokens. Sequence Packing concatenates sequences into mini-batches, maximizing computational efficiency by grouping sequences close to the model's maximum input length. These techniques, combined with Flash Attention, significantly speed up the model's processing.