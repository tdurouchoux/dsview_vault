---
type: Model
---

A hardware-optimized version of the Llama 3.1 8B model, implemented on the Taalas platform. This model achieves near-instantaneous inference speeds (17K tokens/sec per user), with 10X lower power consumption and 20X lower cost compared to traditional GPU-based implementations. It retains flexibility through configurable context windows and support for fine-tuning via low-rank adapters (LoRAs). The model is aggressively quantized, using custom 3-bit and 6-bit parameters in its first generation and standard 4-bit floating-point formats in its second generation.