---
type: Concept
---

FlashAttention is an optimization technique for attention mechanisms in transformers, designed to improve efficiency and performance by reducing memory usage and speeding up computation. It rewrites memory access patterns to minimize the overhead of materializing large intermediate tensors (e.g., the T×T score matrix) in high-bandwidth memory (HBM). By trading slightly more compute for reduced memory input/output (I/O), FlashAttention significantly enhances the efficiency of attention computations on modern GPUs, where memory bandwidth is often the bottleneck. This technique is widely used in transformer architectures, including implementations like Flash Attention 2, to optimize performance during inference and fine-tuning.