---
already_read: false
link: https://jax-ml.github.io/scaling-book/gpus/
read_priority: 5
relevance: 0
source: Alpha Signal
tags:
- Deep_Learning
- Data_Engineering
type: Content
upload_date: '2025-09-19'
---

https://jax-ml.github.io/scaling-book/gpus/
## Summary

The content provides a comprehensive overview of GPUs, focusing on their architecture, networking, and their application in scaling large language models (LLMs). Here are the key technical points and takeaways:

1. **GPU Architecture**:
   - Modern GPUs like H100 and B200 consist of Streaming Multiprocessors (SMs) specialized in matrix multiplication, connected to high-bandwidth memory (HBM).
   - Each SM contains Tensor Cores for matrix operations, Warp Schedulers for vector arithmetic, and shared memory (SMEM) for activations and inputs.
   - GPUs have a hierarchy of memories, including registers, SMEM, L2 cache, and HBM, with varying capacities and bandwidths.

2. **GPU vs. TPU**:
   - GPUs are more flexible and modular compared to TPUs, which have fewer but more powerful Tensor Cores.
   - GPUs can handle a variety of tasks beyond matrix multiplication, making them versatile but harder to optimize for specific tasks like LLMs.

3. **Networking**:
   - GPUs are connected using NVLink for high-bandwidth, low-latency communication within a node, and InfiniBand for communication between nodes.
   - The networking topology is a fat tree, ensuring full bisection bandwidth between any two nodes.
   - The cost of collectives like AllGather and AllReduce depends on whether they are performed within a node or across nodes, with different bandwidths and latencies.

4. **Collectives on GPUs**:
   - GPUs support collectives like AllGather, ReduceScatter, AllReduce, and AllToAll, with different costs depending on the level of parallelism and the networking topology.
   - In-network reductions (SHARP) can reduce the cost of AllReduces by performing reductions within the network switches.

5. **Rooflines for LLM Scaling**:
   - Data parallelism requires a per-GPU batch size of about 2500 tokens to be compute-bound on an H100 or B200.
   - Tensor parallelism is compute-bound up to about 8-ways but becomes communication-bound beyond that.
   - Expert parallelism can span multiple nodes if the feed-forward dimension F is large enough, allowing for significant cross-node expert parallelism.
   - Pipeline parallelism has a low communication cost and is often used to reduce the cost of data parallelism.

6. **Examples and Case Studies**:
   - DeepSeek V3 uses a combination of expert parallelism, pipeline parallelism, and data parallelism to train efficiently on H800 GPUs.
   - LLaMA-3 uses a combination of tensor parallelism, pipeline parallelism, and data parallelism to train efficiently on H100 GPUs.

7. **Acknowledgements and Further Reading**:
   - The content acknowledges contributions from various experts and provides references to further reading on GPU architecture, networking, and LLM training.

In summary, the content provides a detailed technical overview of GPUs, their networking, and their application in scaling LLMs, with a focus on understanding the rooflines and trade-offs involved in different parallelism strategies.
## Links

- [NVIDIA H100 GPU Architecture and Performance Analysis](https://chipsandcheese.com/p/nvidias-h100-funny-l2-and-tons-of-bandwidth) : An in-depth analysis of the NVIDIA H100 GPU architecture, focusing on its L2 cache and bandwidth capabilities.
- [Understanding GPU Architecture](https://cvw.cac.cornell.edu/gpu-architecture) : A comprehensive guide to understanding the architecture of GPUs, including their components and functionalities.
- [NVIDIA SHARP: In-Network Computing](https://developer.nvidia.com/blog/advancing-performance-with-nvidia-sharp-in-network-computing/) : An article explaining NVIDIA's SHARP technology, which enables in-network computing for improved performance in GPU clusters.
- [NVIDIA Megatron-LM Repository](https://github.com/NVIDIA/Megatron-LM) : The GitHub repository for NVIDIA's Megatron-LM, a large-scale transformer language model.
- [NVIDIA NVSwitch HotChips 2022 Presentation](https://hc34.hotchips.org/assets/program/conference/day2/Network%20and%20Switches/NVSwitch%20HotChips%202022%20r5.pdf) : A presentation on NVIDIA's NVSwitch technology, detailing its architecture and performance benefits.

## Topics

![[topics/Concept/GPU]]

![[topics/Concept/Streaming Multiprocessors SMs]]

![[topics/Concept/Tensor Core]]

![[topics/Concept/CUDA Core]]

![[topics/Concept/High Bandwidth Memory HBM]]

![[topics/Concept/NVLink]]

![[topics/Concept/InfiniBand]]

![[topics/Concept/Collective Communication]]

![[topics/Concept/Model Parallelism]]