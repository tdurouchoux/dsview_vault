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

BitNet is an official inference framework for 1-bit LLMs, developed by Microsoft. It supports fast and lossless inference of 1.58-bit models on CPU and GPU, with NPU support planned for the future. The framework offers significant performance improvements and energy efficiency on both ARM and x86 CPUs. Key features include:

- Speedups ranging from 1.37x to 6.17x on different CPU architectures.
- Energy consumption reductions between 55.4% to 82.2%.
- Support for running large models like a 100B BitNet b1.58 model on a single CPU.
- Optimized kernels for various model configurations and hardware setups.

The framework is based on the llama.cpp framework and utilizes Lookup Table methodologies from T-MAC. It supports several models, including BitNet, Llama3, and Falcon families. Installation and usage instructions are provided, along with benchmarking tools and conversion scripts for different model formats. The project is open-source under the MIT license.
## Links

- [BitNet-b1.58-2B-4T Model on Hugging Face](https://huggingface.co/microsoft/BitNet-b1.58-2B-4T) : Hugging Face page for the BitNet-b1.58-2B-4T model, providing access to the model and related resources.
- [bitnet_b1_58-3B Model on Hugging Face](https://huggingface.co/1bitLLM/bitnet_b1_58-3B) : Hugging Face page for the bitnet_b1_58-3B model, offering details and access to the model.
- [bitnet_b1_58-large Model on Hugging Face](https://huggingface.co/1bitLLM/bitnet_b1_58-large) : Hugging Face page for the bitnet_b1_58-large model, providing access to the model and related resources.
- [Llama3-8B-1.58-100B-tokens Model on Hugging Face](https://huggingface.co/HF1BitLLM/Llama3-8B-1.58-100B-tokens) : Hugging Face page for the Llama3-8B-1.58-100B-tokens model, offering details and access to the model.

## Topics

![](topics/Model/BitNet%20b1%2058)

![](topics/Library/bitnet%20cpp)

![](topics/Concept/1%20bit%20LLMs)