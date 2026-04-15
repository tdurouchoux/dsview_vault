---
type: Concept
---

Quantization is a technique used to reduce the precision of model parameters in AI models, typically from floating-point to lower-precision formats like 8-bit, 4-bit, or even 3-bit integers. This process reduces the memory footprint and computational requirements of models, making them faster and more efficient, especially during inference. Quantization is particularly important for hardware-optimized models, large language models (LLMs), and other complex models, where the trade-off between model size and performance is crucial. 

By reducing precision, quantization allows for more efficient use of hardware resources, enabling the deployment of larger models on resource-constrained devices. Techniques such as post-training quantization or quantization-aware training are often employed to maintain model performance while reducing size and improving inference speed. Overall, quantization significantly enhances the model's efficiency in terms of memory usage and computational speed, making it more practical to deploy and run in constrained environments.