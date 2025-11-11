---
type: Concept
---

MXFP4 (Mixed Precision Floating Point 4) is a quantization scheme used to optimize the memory and computational efficiency of large language models (LLMs). This optimization allows models to run on single GPU devices by reducing the precision of the model's weights and activations. MXFP4 is particularly useful for running large models on consumer-grade hardware, as it significantly reduces the memory footprint without sacrificing performance. The gpt-oss models, for example, utilize MXFP4 quantization to fit onto single GPUs, making them more accessible for local and private use.