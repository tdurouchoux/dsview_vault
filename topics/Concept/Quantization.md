---
type: Concept
---

Quantization is a technique used to reduce the precision of numerical representations, such as model parameters or embedding vectors, in AI systems. This process typically converts high-dimensional or high-precision data (e.g., floating-point numbers) into lower-precision formats like 8-bit, 4-bit, or even binary representations. The primary goal is to reduce storage and computational requirements, making models and embeddings more efficient in terms of memory usage and processing speed. 

Quantization is widely applied in AI models, including large language models (LLMs) and hardware-optimized systems, where the trade-off between model size and performance is critical. Techniques such as post-training quantization or quantization-aware training are often employed to maintain performance while achieving efficiency gains. Additionally, quantization enables the deployment of larger models on resource-constrained devices, enhancing their practicality in real-world applications. 

In the context of vector data, quantization (also referred to as Vector Quantization) helps reduce the memory footprint of vectors by mapping high-dimensional vectors to a lower-dimensional space or discrete values. Formats such as half-precision (bf16, f16), quarter-precision (e5m2, e4m3), and integer representations (e.g., i8) are commonly used to optimize memory usage and computational efficiency without significantly sacrificing accuracy.