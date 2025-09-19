---
type: Concept
---

Collective communication refers to the set of operations used to synchronize and share data between multiple GPUs or nodes in a parallel computing environment. Common collective operations include AllGather, AllReduce, ReduceScatter, and AllToAll, which are essential for distributed training of machine learning models. These operations are implemented using libraries like NCCL (NVIDIA Collective Communications Library) and NVSHMEM, which optimize communication patterns for high-performance computing. Efficient collective communication is crucial for minimizing latency and maximizing throughput in large-scale machine learning and data science applications.