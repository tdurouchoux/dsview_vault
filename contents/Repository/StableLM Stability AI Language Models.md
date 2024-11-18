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

3. **StableVicuna**: A fine-tuned version of Vicuna-13B, developed for open-source RLHF chatbot applications, with delta weights released under a non-commercial license.

The models are evaluated using zero-shot benchmarks, with StableLM-3B-4E1T achieving competitive performance against other contemporary models. The repository also provides code snippets for running inference and examples of creative outputs, including conversations and creative writing.

Licensing for the models varies, with base models under CC BY-SA-4.0 and fine-tuned models under CC BY-NC-SA-4.0. The repository encourages community involvement and feedback to improve model responses.
## Links

1. [StableLM-3B-4E1T Model](https://huggingface.co/stabilityai/stablelm-3b-4e1t) - Access the StableLM-3B-4E1T model hosted on Hugging Face for various applications.
2. [StableLM Base Alpha 3B Model](https://huggingface.co/stabilityai/stablelm-base-alpha-3b-v2) - Explore the StableLM Base Alpha 3B model for foundational language model tasks.
3. [Evaluation Harness for Language Models](https://github.com/EleutherAI/lm-evaluation-harness/tree/df3da98c5405deafd519c2ddca52bb7c3fe36bef) - A repository for evaluating language models, useful for benchmarking performance.
4. [Falcon RefinedWeb Dataset](https://huggingface.co/datasets/tiiuae/falcon-refinedweb) - A dataset used for training language models, providing a rich source of web data.
5. [RedPajama Dataset](https://github.com/togethercomputer/RedPajama-Data) - A dataset that contributes to the training of language models, enhancing their performance and capabilities.
## Topics

![](topics/Library/StableLM)

![](topics/Model/StableLM%203B%204E1T)

![](topics/Model/StableLM%20Alpha%20v2)

![](topics/Model/StableVicuna%2013B)

![](topics/Dataset/Falcon%20RefinedWeb)