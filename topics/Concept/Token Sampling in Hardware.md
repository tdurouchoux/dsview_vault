---
type: Concept
---

Token sampling in hardware refers to the process of selecting the next token in a generative model directly within the FPGA fabric, rather than offloading this task to a host program. In Talos V2, the categorical sampler computes weights, accumulates them, scales a random cutoff, and selects the next token entirely in RTL. This approach reduces latency and improves throughput by eliminating the need for data transfer between the FPGA and host system, while also ensuring that the sampling process adheres to the model's probabilistic behavior.