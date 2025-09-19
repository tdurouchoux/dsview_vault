---
type: Concept
---

Streaming Multiprocessors (SMs) are the core processing units within a GPU, responsible for executing computational tasks. Each SM contains multiple components, including Tensor Cores for matrix multiplications, CUDA cores for general-purpose computing, and shared memory (SMEM) for fast data access. The number of SMs varies by GPU model, with higher-end models like the NVIDIA H100 and B200 having more SMs to handle larger workloads. SMs operate independently but can coordinate to maximize performance, making them essential for parallel processing in machine learning and data science.