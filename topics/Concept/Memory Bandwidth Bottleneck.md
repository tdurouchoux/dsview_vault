---
type: Concept
---

The Memory Bandwidth Bottleneck refers to the limitation imposed by the speed at which data can be transferred between high-bandwidth memory (HBM) and static random-access memory (SRAM) in modern GPUs. This bottleneck is a critical consideration in designing efficient transformer architectures, as operations like torch.stack() that require contiguous memory allocations can become major performance hurdles. Techniques like FlashAttention address this bottleneck by optimizing memory access patterns to minimize data movement.