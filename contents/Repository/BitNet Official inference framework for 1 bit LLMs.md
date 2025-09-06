---
already_read: true
link: https://github.com/microsoft/BitNet
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2024-10-22'
---

https://github.com/microsoft/BitNet
## Summary

BitNet is an official inference framework for 1-bit LLMs, developed by Microsoft. It supports fast and lossless inference of 1.58-bit models on CPU and GPU, with NPU support planned for the future. The framework offers optimized kernels that provide significant speedups and energy reductions on both ARM and x86 CPUs. Key features include:

- Speedups of 1.37x to 5.07x on ARM CPUs and 2.37x to 6.17x on x86 CPUs.
- Energy consumption reductions of 55.4% to 70.0% on ARM and 71.9% to 82.2% on x86.
- Ability to run a 100B BitNet b1.58 model on a single CPU at human reading speeds (5-7 tokens per second).

The framework supports various models and provides scripts for benchmarking and converting models. It is built on top of the llama.cpp framework and utilizes Lookup Table methodologies from T-MAC. Installation and usage instructions are provided for different operating systems, with detailed steps for building from source and running inference. The project is open-source under the MIT license.
## Links

- [BitNet Demo](https://bitnet-demo.azurewebsites.net/) : A demo of BitNet running a BitNet b1.58 3B model on Apple M2.
- [BitNet-b1.58-2B-4T Model on Hugging Face](https://huggingface.co/microsoft/BitNet-b1.58-2B-4T) : The BitNet-b1.58-2B-4T model available on Hugging Face.
- [BitNet Technical Report](https://arxiv.org/abs/2410.16144) : Technical report detailing the performance and efficiency gains of BitNet on CPUs.
- [BitNet GPU Inference Kernel](https://arxiv.org/abs/2502.11880) : Details about the official GPU inference kernel for BitNet.
- [BitNet on Hugging Face](https://huggingface.co/1bitLLM/bitnet_b1_58-large) : The BitNet-b1.58-large model available on Hugging Face.

## Topics

![](topics/Model/BitNet%20b1%2058)

![](topics/Library/bitnet%20cpp)

![](topics/Concept/1%20bit%20LLMs)

![](topics/Concept/Quantization)