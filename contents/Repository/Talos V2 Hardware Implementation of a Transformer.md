---
already_read: false
link: https://v2.talos.wtf/
read_priority: 5
relevance: 0
source: Alpha Signal
tags:
- Computer_Vision
type: Content
upload_date: '2026-05-05'
---

https://v2.talos.wtf/
## Summary

Talos V2 is a hardware implementation of a small Transformer (microGPT) designed as a learning tool, achieving >50k tokens/s on a Cyclone V FPGA. The project translates the Transformer inference path into explicit RTL, covering embeddings, attention, normalization, MLP, and token sampling. Key technical points include:

- **Core RTL Architecture**: Uses Q4.12 fixed-point math (16-bit signed values) for efficiency. Weights are pre-loaded into ROMs to avoid runtime movement overhead.
- **Reusable MatVec Tile**: A 16-lane systolic matrix-vector tile handles all matrix-vector operations (e.g., Q/K/V projections, MLP), time-multiplexed across layers to balance area and throughput.
- **Attention in Hardware**: Implements attention as a scheduled RTL pipeline, including softmax approximation via LUTs, multicycle division, and parallel processing of attention channels to reduce bottlenecks.
- **Optimizations**: Focused on reducing cycles, shortening critical paths, and avoiding unnecessary parallelism. Techniques include operation folding (e.g., combining max tracking with dot-product passes), multicycle math engines (e.g., RMS normalization), and hardware token sampling with improved randomness.
- **Performance**: Achieves ~53k tokens/s on DE1-SoC, with speedups from disciplined hardware decisions (local weights, streaming data, clock tuning post-timing closure).
- **Learning Focus**: Demonstrates how model operations translate to hardware constraints (area, memory bandwidth, routing) and provides a reusable RTL framework for further exploration. Open-source with room for improvements (e.g., tighter scheduling, better memory reuse).
## Links

- [Attention Is All You Need Paper](https://arxiv.org/abs/1706.03762) : This is the foundational paper on Transformers, titled *Attention Is All You Need*, which introduces the core Transformer architecture. The RTL design in Talos V2 is derived from this formulation, making this link highly relevant for understanding the mathematical and architectural basis of the project.
- [Karpathy's microGPT Guide](https://karpathy.github.io/2026/02/12/microgpt/) : This guide provides a single-file reference implementation and walkthrough of a compact autoregressive GPT model. It is directly referenced in the Talos V2 project as the model used for hardware implementation, making it essential for understanding the software-to-hardware translation process.
- [Cornell DE1-SoC Memory Notes](https://people.ece.cornell.edu/land/courses/ece5760/DE1_SOC/Memory/index.html) : This resource details practical ROM and on-chip memory usage patterns on the DE1-SoC Cyclone V platform. It is highly relevant as it shaped the memory layout, tile width, and overall hardware constraints in the Talos V2 project.
- [Talos V2 GitHub Repository](https://github.com/Luthiraa/TALOS-V2) : This is the open-source repository for the Talos V2 project, containing the full RTL implementation, documentation, and design files. It is the most critical link for exploring the project in depth, understanding the hardware design, and potentially contributing to its development.

## Topics

![[topics/Model/microGPT]]

![[topics/Tool/RTL Register Transfer Level]]

![[topics/Concept/Fixed Point Arithmetic Q4 12]]

![[topics/Concept/Systolic Array]]

![[topics/Concept/Attention Mechanism in Hardware]]

![[topics/Concept/Lookup Table LUT based Approximation]]

![[topics/Concept/Time Multiplexing]]

![[topics/Concept/Critical Path Optimization]]

![[topics/Platform/DE1 SoC Cyclone V]]

![[topics/Concept/Token Sampling in Hardware]]