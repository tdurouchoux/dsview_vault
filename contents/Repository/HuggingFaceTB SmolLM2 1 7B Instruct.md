---
already_read: false
link: https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct
read_priority: 4
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2025-01-08'
---

https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct
## Summary

SmolLM2 is a family of compact language models available in three sizes: 135M, 360M, and 1.7B parameters. The 1.7B variant shows significant improvements over its predecessor, SmolLM1-1.7B, in instruction following, knowledge, reasoning, and mathematics. It was trained on 11 trillion tokens using a diverse dataset combination and fine-tuned with supervised fine-tuning (SFT) and Direct Preference Optimization (DPO).

The model supports tasks such as text rewriting, summarization, and function calling. Evaluation results show that SmolLM2 outperforms its predecessor and other models like Llama-1B and Qwen2.5-1.5B in various benchmarks.

To use the model, you can install the Transformers library and load the model using the provided code snippets. The model can also be used with the TRL CLI for chatting from the terminal or with Transformers.js for web-based applications.

The model has limitations, such as primarily understanding and generating content in English and potential inaccuracies or biases in the generated content. It is recommended to use the model as an assistive tool and verify important information.

The model was trained using 256 H100 GPUs and the nanotron training framework. It is licensed under Apache 2.0, and a citation is provided for academic use.

The model card includes sections on how to use the model, evaluation results, examples, limitations, training details, license, and citation. The model is available for download and can be used with various inference providers.
## Links

- [SmolLM2 Research Paper](https://arxiv.org/abs/2502.02737v1) : Research paper detailing the development and capabilities of the SmolLM2 model family.
- [SmolLM2 GitHub Repository](https://github.com/huggingface/smollm) : GitHub repository containing the code for pre-training, post-training, evaluation, and local inference of SmolLM2 models.
- [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) : License under which the SmolLM2 models are distributed.

## Topics

![](topics/Model/SmolLM2)

![](topics/Dataset/FineWeb%20Edu)

![](topics/Dataset/DCLM)

![](topics/Dataset/The%20Stack)

![](topics/Concept/UltraFeedback)

![](topics/Dataset/Synth%20APIGen%20v0%201)

![](topics/Concept/Nanotron)

![](topics/Concept/Direct%20Preference%20Optimization%20DPO)

![](topics/Concept/Supervised%20Fine%20Tuning%20SFT)