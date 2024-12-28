---
already_read: true
link: https://github.com/deepseek-ai/DeepSeek-V3
read_priority: 1
source: Alpha Signal
tags:
- Large_Language_Model
- Deep_Learning
type: Content
upload_date: '2024-12-28'
---

https://github.com/deepseek-ai/DeepSeek-V3
## Summary

DeepSeek-V3 is a Mixture-of-Experts (MoE) language model with 671 billion parameters, utilizing 37 billion activated parameters per token. It features Multi-head Latent Attention (MLA) and DeepSeekMoE architectures, enhancing inference efficiency and training cost-effectiveness. Key innovations include an auxiliary-loss-free load balancing strategy and a multi-token prediction training objective, leading to superior performance compared to other models.

The model was pre-trained on 14.8 trillion tokens, followed by supervised fine-tuning and reinforcement learning, achieving high stability during training with minimal resource requirements (2.788 million GPU hours). Evaluation results indicate that DeepSeek-V3 outperforms many open-source models and competes with leading closed-source models across various benchmarks, particularly in math and code tasks.

DeepSeek-V3 can be deployed locally using various frameworks and supports FP8 mixed precision training. The repository provides detailed instructions for local deployment, model weight conversion, and inference using different tools. The project is licensed under MIT, allowing for commercial use.
## Links

1. [Hugging Face - DeepSeek-V3](https://huggingface.co/deepseek-ai/DeepSeek-V3) - Access the DeepSeek-V3 model and its weights on Hugging Face.
2. [NVIDIA TensorRT-LLM for DeepSeek-V3](https://github.com/NVIDIA/TensorRT-LLM/tree/deepseek/examples/deepseek_v3) - Explore the custom branch of TensorRT-LLM specifically for DeepSeek-V3 support.
3. [SGLang - DeepSeek-V3 Benchmark](https://github.com/sgl-project/sglang/tree/main/benchmark/deepseek_v3) - Check out the SGLang framework that supports DeepSeek-V3 for efficient inference.
4. [LMDeploy - DeepSeek-V3 Integration](https://github.com/InternLM/lmdeploy/issues/2960) - Find instructions for running DeepSeek-V3 with the LMDeploy framework.
5. [MindIE Framework for Huawei Ascend](https://www.hiascend.com/en/software/mindie) - Learn about the MindIE framework that adapts DeepSeek-V3 for Huawei Ascend devices.
## Topics

![](topics/Model/DeepSeek%20V3)

![](topics/Concept/Multi%20head%20Latent%20Attention%20MLA)

![](topics/Concept/Multi%20Token%20Prediction%20MTP)

![](topics/Tool/SGLang)

![](topics/Tool/LMDeploy)