---
already_read: false
link: https://github.com/Stability-AI/StableLM
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2023-04-20'
---

https://github.com/Stability-AI/StableLM
## Summary

The Stability AI GitHub repository for StableLM details ongoing development of a series of language models, featuring various architectures and parameter sizes. Key models include the StableLM-3B-4E1T, which has 3 billion parameters and is trained on a vast dataset, and the StableLM-Alpha v2 models that enhance earlier versions through architectural improvements and higher-quality data sources.

Recent model releases include:
- StableLM-3B-4E1T on September 29, 2023.
- Patched StableLM-Alpha v2 models with 3B and 7B parameters on August 5, 2023.
- StableVicuna-13B, a fine-tuned version of Vicuna-13B, on April 28, 2023.

Training methodologies employ large datasets and specific architectural changes, such as rotary position embeddings and advanced normalization techniques. Notable achievements include state-of-the-art performance at 3B parameter scale compared to other contemporary models.

Models are available for experimentation via Hugging Face, allowing for quick deployment in applications such as conversational AI. The repository emphasizes community engagement and encourages contributions to expand the models' capabilities.

Licensing for the base models follows the CC BY-SA-4.0, while fine-tuned models operate under a non-commercial CC BY-NC-SA-4.0 license. Primary development focuses on zero-shot evaluations to maintain competitive performance in various benchmark tasks.
## Links

- [StableLM on Hugging Face](https://huggingface.co/stabilityai/stablelm-3b-4e1t) : Explore and run inference with the StableLM-3B-4E1T model, a state-of-the-art open-source language model.
- [StableLM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness/tree/lm-bench) : Access to the evaluation harness designed for benchmarking language models like StableLM, including various metrics and tasks.
- [RefinedWeb Dataset](https://huggingface.co/datasets/tiiuae/falcon-refinedweb) : A dataset used for training language models, providing a curated source of web text.
- [StableVicuna Model on Hugging Face](https://huggingface.co/CarperAI/stable-vicuna-13b-delta/) : Details on the StableVicuna model, an RLHF fine-tune of the LLaMA model aimed at chat applications.
- [Stanford Alpaca's Dataset](https://huggingface.co/datasets/RyokoAI/ShareGPT52K) : A collection of datasets used for fine-tuning conversational agents, including those based on Stanford Alpaca.

## Topics

![](topics/Model/StableLM)

![](topics/Dataset/RedPajama%20Data)

![](topics/Library/Transformers)

![](topics/Concept/Reinforcement%20Learning%20from%20Human%20Feedback%20RLHF)

![](topics/Concept/Multi%20Epoch%20Training)

![](topics/Concept/Stochastic%20Parrots)