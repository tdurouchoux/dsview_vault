---
already_read: false
link: https://github.com/pytorch/torchtune
read_priority: 1
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2024-04-29'
---

https://github.com/pytorch/torchtune
## Summary

torchtune is a native PyTorch library designed for fine-tuning large language models (LLMs). Key features include:

- **Modular Design**: Offers native implementations of popular LLMs with composable building blocks.
- **Fine-tuning Techniques**: Supports various methods like LoRA, QLoRA, and full fine-tuning without requiring complex frameworks.
- **Configuration Management**: Utilizes YAML configs for easy setup of training, evaluation, and inference.
- **Integration**: Works with tools like Hugging Face Hub, EleutherAI's LM Eval Harness, and Weights & Biases for enhanced functionality.

Supported models include Llama3, Llama2, Code-Llama2, Mistral, and others, with various sizes available. Fine-tuning recipes cater to both single-device and distributed training scenarios, focusing on memory efficiency.

Installation requires PyTorch and related libraries, with a straightforward command-line interface for running fine-tuning tasks. The library emphasizes usability, simplicity, and correctness, with extensive testing to ensure reliability.

Community contributions are encouraged, and the library is open-source under the BSD-3-Clause license.
## Links

1. [Hugging Face Hub](https://huggingface.co/docs/hub/en/index) - A platform for accessing model weights and datasets for machine learning.
2. [EleutherAI's LM Eval Harness](https://github.com/EleutherAI/lm-evaluation-harness) - A tool for evaluating language models, useful for assessing the performance of fine-tuned models.
3. [Hugging Face Datasets](https://huggingface.co/docs/datasets/en/index) - A library for accessing and managing datasets for training and evaluation in machine learning.
4. [PyTorch FSDP](https://pytorch.org/docs/stable/fsdp.html) - Documentation for PyTorch's Fully Sharded Data Parallel, which is useful for distributed training.
5. [torchao](https://github.com/pytorch-labs/ao) - A library for advanced optimization techniques in PyTorch, including quantization methods.
## Topics

- [[topics/Library/Torchtune]]
- [[topics/Model/Llama 3]]
- [[topics/Library/ExLlamaV2 and Llama2]]
- [[topics/Concept/Fine-tuning]]
- [[topics/Platform/Hugging Face]]