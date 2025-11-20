---
type: Concept
---

Batch-invariant kernels are a solution proposed to address nondeterminism in machine learning inference. These kernels ensure that the order of operations in GPU computations is consistent regardless of the batch size, leading to deterministic results. This is achieved by fixing the reduction order and tile sizes in operations like RMSNorm, matrix multiplication, and attention mechanisms.