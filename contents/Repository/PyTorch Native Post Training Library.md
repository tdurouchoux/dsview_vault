---
already_read: false
link: https://github.com/pytorch/torchtune
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- Development_tool
type: Content
upload_date: '2024-04-29'
---

https://github.com/pytorch/torchtune
## Summary

Torchtune is a PyTorch library designed for post-training large language models (LLMs). It offers hackable training recipes for various tasks such as supervised fine-tuning (SFT), knowledge distillation, direct preference optimization (DPO), proximal policy optimization (PPO), generative reinforcement learning (GRPO), and quantization-aware training. The library supports a wide range of state-of-the-art models like Llama, Gemma, Mistral, Phi, and Qwen, among others.

Key features include:
- **Memory and Performance Optimizations**: Techniques like packed datasets, torch compile, chunked cross-entropy, activation checkpointing, activation offloading, and 8-bit AdamW optimizer are employed to enhance memory efficiency and training speed.
- **Distributed Training**: Supports multi-device and multi-node training configurations.
- **Easy Configuration**: Uses YAML configs for setting up training, evaluation, quantization, or inference recipes.
- **Community and Integrations**: Integrates with popular tools like Hugging Face Hub, EleutherAI's LM Eval Harness, PyTorch FSDP2, and Weights & Biases for logging and tracking.

The library is actively maintained, with recent updates adding support for new models like Qwen3, Llama4, and multi-node training capabilities. It is released under the BSD 3 license and encourages community contributions.
## Links

- [PyTorch TorchTune Installation Guide](https://pytorch.org/torchtune/main/install.html) : This link provides detailed instructions on how to install the TorchTune library, including both stable and nightly releases. It also covers installation from source and verification of the installation.
- [TorchTune Recipes Overview](https://pytorch.org/torchtune/main/recipes/recipes_overview.html) : This link points to the overview of various training recipes supported by TorchTune, including supervised finetuning, knowledge distillation, reinforcement learning, and quantization-aware training.
- [TorchTune Memory Optimizations](https://pytorch.org/torchtune/main/tutorials/memory_optimizations.html) : This link provides tutorials on memory optimizations and performance improvements for training large language models with TorchTune, including techniques like activation checkpointing, packed datasets, and lower precision optimizers.
- [Hugging Face Hub Documentation](https://huggingface.co/docs/hub/en/index) : This link directs to the Hugging Face Hub documentation, which is relevant for accessing model weights and datasets used in TorchTune.
- [Llama Model Documentation](https://www.llama.com/docs/model-cards-and-prompt-formats/llama3_2) : This link provides documentation for the Llama models, including model cards and prompt formats, which are supported and used in TorchTune for finetuning and other post-training tasks.

## Topics

![[topics/Concept/LoRA Low Rank Adaptation]]

![[topics/Concept/Quantization Aware Training QAT]]

![[topics/Library/Torchtune]]

![[topics/Concept/Reinforcement Learning from Human Feedback RLHF]]

![[topics/Concept/Knowledge Distillation]]

![[topics/Concept/QLoRA]]