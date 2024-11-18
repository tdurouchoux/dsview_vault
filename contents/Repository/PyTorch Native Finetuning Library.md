---
already_read: false
link: https://github.com/pytorch/torchtune
read_priority: 1
source: null
tags:
- Large_Language_Model
- Deep_Learning
type: Content
upload_date: '2024-04-29'
---

https://github.com/pytorch/torchtune
## Summary

torchtune is a PyTorch library designed for fine-tuning and experimenting with large language models (LLMs). Key features include:

- Support for popular LLMs like Llama, Gemma, Mistral, Phi, and Qwen.
- Hackable training recipes for various fine-tuning methods, including full fine-tuning, LoRA, QLoRA, and knowledge distillation.
- Out-of-the-box memory efficiency and performance improvements.
- YAML configuration files for easy setup of training, evaluation, and inference.

Recent updates include support for new models and features such as activation offloading and multimodal QLoRA. The library provides detailed finetuning recipes for different devices and methods, along with memory and training speed metrics.

Installation is straightforward, with options for stable and nightly releases. The library integrates with popular tools like Hugging Face Hub and Weights & Biases for enhanced functionality.

Community contributions are encouraged, and the library is open-source under the BSD-3-Clause license.
## Links

1. [Hugging Face Datasets](https://huggingface.co/docs/datasets/en/index) - Comprehensive documentation on using datasets for training and evaluation in machine learning.
2. [Hugging Face Hub for accessing model weights](https://huggingface.co/meta-llama) - Access and manage model weights for Llama and other models.
3. [Weights & Biases for logging metrics](https://wandb.ai/site) - A platform for tracking experiments, visualizing metrics, and sharing results in machine learning projects.
4. [EleutherAI's LM Eval Harness](https://github.com/EleutherAI/lm-evaluation-harness) - A tool for evaluating language models across various benchmarks.
5. [PyTorch FSDP2 for distributed training](https://github.com/pytorch/torchtitan/blob/main/docs/fsdp.md) - Documentation on using Fully Sharded Data Parallel for efficient distributed training in PyTorch.
## Topics

![](topics/Library/torchtune)

![](topics/Concept/Finetuning%20Recipes)

![](topics/Model/Llama%20Series)

![](topics/Product/torchvision)

![](topics/Product/torchao)