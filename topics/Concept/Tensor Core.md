---
type: Concept
---

Tensor Cores are specialized units within a GPU's Streaming Multiprocessor (SM) designed to accelerate matrix multiplications, a critical operation in machine learning and data science. Each Tensor Core can perform a large number of floating-point operations per second (FLOPs), significantly speeding up tasks like training neural networks. Modern GPUs, such as the NVIDIA H100 and B200, have multiple Tensor Cores per SM, enabling high-throughput computations. Tensor Cores support various precision levels, including FP16, BF16, and FP8, allowing for efficient processing of different data types.