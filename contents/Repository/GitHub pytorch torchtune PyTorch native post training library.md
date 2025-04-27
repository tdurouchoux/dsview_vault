---
already_read: false
link: https://github.com/pytorch/torchtune
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2024-04-29'
---

https://github.com/pytorch/torchtune
## Summary

torchtune is a PyTorch library designed for post-training processes focused primarily on large language models (LLMs). Key features include:

- **Post-Training Methods**: Supports various techniques such as Supervised Fine-tuning (SFT), Knowledge Distillation (KD), and Reinforcement Learning from Human Feedback (RLHF), among others.
- **Model Support**: Works with multiple state-of-the-art models, including Llama, Gemma, Mistral, and others, with ongoing additions.
- **Performance Optimization**: Offers techniques for improving memory efficiency and training speed, utilizing PyTorch APIs for high performance.
- **Configurable Training**: Users can easily set YAML configurations for training, evaluation, and quantization.
- **Installation**: Compatible with the latest stable and nightly releases of PyTorch, with commands provided for both environments.
- **Community Integration**: Collaborates with tools like Hugging Face, Weights & Biases, and others for evaluation, logging, and training support.

Recent updates highlight support for new models and various enhancements aimed at improving user experience and tool capabilities. Users are encouraged to participate by contributing improvements and new training recipes.
## Links

- [Hugging Face Model Hub](https://huggingface.co/models) : A platform to discover and share pretrained models for various machine learning tasks.
- [PyTorch Quantization Aware Training (QAT) Recipe](https://pytorch.org/torchtune/stable/recipes/qat_distributed.html) : Instructions on how to implement quantization-aware training in PyTorch.
- [Memory Optimizations in torchtune](https://pytorch.org/torchtune/main/tutorials/memory_optimizations.html) : A tutorial detailing methods for optimizing memory usage when training large language models.
- [Hugging Face PEFT Library](https://github.com/huggingface/peft) : A library offering methods for parameter-efficient fine-tuning of models.
- [End-to-End Workflow Tutorial](https://pytorch.org/torchtune/main/tutorials/e2e_flow.html) : A tutorial providing a complete guide from pretraining to inference for LLMs in torchtune.

## Topics

![](topics/Library/torchtune)

![](topics/Concept/Supervised%20Finetuning%20SFT)

![](topics/Concept/Knowledge%20Distillation%20KD)

![](topics/Concept/Reinforcement%20Learning%20from%20Human%20Feedback%20RLHF)

![](topics/Model/Llama4)

![](topics/Model/Qwen2)