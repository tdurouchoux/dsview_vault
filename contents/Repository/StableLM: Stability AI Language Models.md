---
already_read: false
link: https://github.com/Stability-AI/StableLM
read_priority: 1
source: null
tags:
- Large_Language_Model
- Natural_Language_Processing
type: Content
upload_date: '2023-04-20'
---

https://github.com/Stability-AI/StableLM
## Summary

The Stability AI repository for StableLM focuses on the development of a series of language models, with ongoing updates and new checkpoints. Key models include:

1. **StableLM-3B-4E1T**: A 3 billion parameter model trained on 1 trillion tokens over 4 epochs, designed to assess the impact of repeated tokens on performance. It features a decoder-only transformer architecture similar to LLaMA, with rotary position embeddings and LayerNorm normalization.

2. **StableLM-Alpha v2**: An improvement over the initial Alpha models, utilizing higher-quality data sources and architectural enhancements like SwiGLU. It includes models with 3B and 7B parameters, trained on 1.1 trillion tokens.

3. **StableVicuna-13B**: A fine-tuned model based on Vicuna-13B, developed for open-source RLHF chatbot applications.

The models are evaluated using various benchmarks, with StableLM-3B-4E1T achieving state-of-the-art performance among open-source models at the 3B scale. The repository also provides code snippets for running inference and highlights potential issues with pretrained models, such as varying response quality and the risk of offensive content.

Licensing details include Creative Commons licenses for base and fine-tuned models, and the repository is open for contributions and community feedback.
## Links

1. [Hugging Face Spaces](https://huggingface.co/spaces/stabilityai/stablelm-tuned-alpha-chat) - A platform to interact with the StableLM-Tuned-Alpha model.
2. [StableLM-3B-4E1T Technical Report](https://stability.wandb.io/stability-llm/stable-lm/reports/StableLM-3B-4E1T--VmlldzoyMjU4?accessToken=u3zujipenkx5g7rtcj9qojjgxpconyjktjkli2po09nffrffdhhchq045vp0wyfo) - Detailed report on the StableLM-3B-4E1T model's architecture and performance.
3. [Muennighoff et al. (2023)](https://arxiv.org/abs/2305.16264) - Research paper discussing scaling data-constrained language models.
4. [Touvron et al. (2023)](https://arxiv.org/abs/2307.09288) - Research paper on the LLaMA architecture, which is relevant to the model discussed.
5. [Gao et al. (2020)](https://arxiv.org/abs/2101.00027) - Research paper on The Pile dataset, which is used in training the models mentioned.
## Topics

- [[topics/Model/StableLM]]
- [[topics/Model/StableLM-3B-4E1T]]
- [[topics/Model/StableLM-Alpha v2]]
- [[topics/Concept/Diffusion and Stable Diffusion]]
- [[topics/Library/Hugging Face]]