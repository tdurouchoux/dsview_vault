---
already_read: false
link: https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct
read_priority: 4
relevance: 0
source: null
tags:
- Large_Language_Model
- Natural_Language_Processing
type: Content
upload_date: '2025-01-08'
---

https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct
## Summary

SmolLM2 is a family of compact language models with sizes of 135M, 360M, and 1.7B parameters, designed for on-device applications. The 1.7B variant shows improvements in instruction following, reasoning, and mathematics compared to its predecessor, trained on 11 trillion tokens from diverse datasets. It supports tasks like text rewriting, summarization, and function calling, enhanced through supervised fine-tuning and Direct Preference Optimization.

To use the model, install the `transformers` library and load the model with the provided code snippets. Evaluation metrics indicate strong performance across various benchmarks, outperforming previous models in several tasks. However, the model primarily understands English and may produce factually inaccurate or biased content, necessitating user verification.

The training utilized a transformer decoder architecture on 256 H100 GPUs, with a focus on bfloat16 precision. The model is licensed under Apache 2.0, and further details can be found in the provided citation.
## Links

1. [Hugging Face Datasets](https://huggingface.co/datasets/HuggingFaceTB/smoltalk) - A dataset used for supervised fine-tuning of the SmolLM2 model.
2. [Hugging Face GitHub - SmolLM](https://github.com/huggingface/smollm) - Repository containing pre-training, post-training, evaluation, and local inference code for the SmolLM models.
3. [Hugging Face GitHub - Lighteval](https://github.com/huggingface/lighteval) - A tool used for evaluating the performance of language models, relevant for the evaluation section of SmolLM2.
4. [Hugging Face Datasets - Synth-APIGen](https://huggingface.co/datasets/argilla/Synth-APIGen-v0.1) - A dataset developed for instruction following tasks, used in the SmolLM2 model.
5. [Hugging Face Docs - Safetensors](https://huggingface.co/docs/safetensors) - Documentation on Safetensors, which may be relevant for understanding model storage and performance.
## Topics

![](topics/Model/SmolLM2)

![](topics/Tool/Transformer%20Tools)

![](topics/Tool/TensorBoard)

![](topics/Tool/ONNX)

![](topics/Concept/Direct%20Preference%20Optimization%20DPO)