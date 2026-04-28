---
already_read: false
link: https://www.evanlin.ca/writing/exploring-attnres
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Deep_Learning
type: Content
upload_date: '2026-04-28'
---

https://www.evanlin.ca/writing/exploring-attnres
## Summary

The post details a hands-on exploration of the **Attention Residuals** paper (Kimi Team, 2026) by reimplementing it from scratch in PyTorch. Key technical takeaways:

1. **Core Idea**: Attention Residuals replace standard residual connections with a learned routing mechanism, allowing each layer to dynamically select and blend outputs from all previous layers (depth-wise caching), unlike standard attention which caches tokens (breadth-wise).

2. **Implementation**:
   - **History Database**: Maintains a list of all intermediate outputs (embedding, MHA/MLP outputs per layer) as pointers (O(1) append cost).
   - **Alpha Gate**: A 4-step learned router (RMSNorm → scoring → softmax → blending) that computes softmax-normalized weights to mix past states before feeding them to MHA/MLP.
   - **Dual Norms**: Separate RMSNorms for routing (inside alpha gate) and pre-norms (before MHA/MLP) to stabilize scoring and prevent gradient explosion.

3. **Key Observations**:
   - **Gradient Flow**: Alpha gates create direct gradient paths, leading to 11× gradient growth in early layers (vs. 1.8× for standard residuals) and lower final loss (0.830 vs. 0.865) in a synthetic sequence-reversal task.
   - **Memory Cost**: `torch.stack()` is expensive (copies data into contiguous memory) but necessary for GPU parallelism (einsum requires aligned tensors).

4. **Hardware Insights**:
   - Highlights trade-offs between compute and memory bandwidth (e.g., FlashAttention’s memory access optimizations).
   - Emphasizes the gap between abstract math and physical silicon constraints (e.g., softmax parallelism, list vs. tensor memory models).

5. **Comparison to Paper**:
   - Reproduces the paper’s core findings (gradient uniformity, lower loss) despite vastly different scales (4-layer toy model vs. 48B-parameter MoE).
   - Notes limitations like the "useless" first alpha gate (queries only the embedding) and suggests future work (e.g., Block AttnRes, RoPE).

**Why It Matters**: The exercise bridges theory and practice, revealing implementation nuances critical for debugging, hardware design, or novel architectures. Full code is available in the linked repository.
## Links

- [Attention Residuals Paper (Kimi Team, 2026)](https://arxiv.org/abs/2603.15031) : This is the original research paper titled 'Attention Residuals' by the Kimi Team (2026). It introduces the concept of attention residuals, a mechanism that enables layers in a transformer to directly query and route information from previous layers, improving gradient flow and reducing the dilution of early-layer signals. The paper is the primary source of inspiration for the content discussed in the provided text.
- [GitHub Repository for Toy Attention Residuals](https://github.com/eevaain/toy-attention-residuals) : This GitHub repository contains the full implementation of the 'Attention Residuals' concept as reimplemented from scratch in PyTorch. It includes the code, training logs, and other artifacts referenced in the provided content. The repository is a practical resource for understanding the implementation details and experimenting with the architecture.
- [YouTube Video on Attention Mechanisms](https://www.youtube.com/watch?v=LSHTkbnmzy4) : This YouTube video provided initial intuition about attention mechanisms and how they route information in transformers. It served as a foundational resource for the author before diving into the reimplementation of the 'Attention Residuals' paper. The video likely explains attention in a more accessible way, helping bridge the gap between abstract math and practical implementation.

## Topics

![[topics/Concept/Attention Residuals]]

![[topics/Concept/Alpha Gate]]

![[topics/Concept/History Database]]

![[topics/Concept/Gradient Highways]]

![[topics/Concept/Pre norms and Routing Norms]]

![[topics/Concept/FlashAttention]]

![[topics/Concept/Memory Bandwidth Bottleneck]]