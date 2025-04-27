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

SmolLM2 is a series of compact language models available in three sizes: 135M, 360M, and 1.7B parameters. The 1.7B variant shows notable improvements in instruction following, knowledge, reasoning, and math over its predecessor. It was trained on 11 trillion tokens from a variety of datasets and has undergone supervised fine-tuning (SFT) and Direct Preference Optimization (DPO).

The instruct model supports tasks like text rewriting, summarization, and function calling, leveraging specialized datasets. Users can implement the model easily using the Transformers library, either in Python or JavaScript.

Evaluation results indicate strong performance across various benchmarks, including HellaSwag, ARC, and others, outperforming several competitors in many metrics. However, the model is primarily English-focused and may produce inaccurate or biased content, requiring users to verify important information.

The SmolLM2 architecture is built on transformers, employing a pre-training regime focused on extensive token input. It is trained on 256 H100 GPUs using the nanotron framework and is licensed under Apache 2.0. Detailed documentation and dataset links are available for further exploration.
## Links

- [SmolLM2 Model Paper](https://arxiv.org/abs/2502.02737v1) : The research paper detailing the SmolLM2 model, its architecture, training data, and evaluation metrics.
- [Hugging Face Datasets](https://huggingface.co/datasets/HuggingFaceTB/smoltalk) : The dataset used for supervised fine-tuning of the SmolLM2 model.
- [Function Calling Instructions](https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct/blob/main/instructions_function_calling.md) : Detailed instructions on how to implement function calling with the SmolLM2 model.
- [Alignment Handbook](https://github.com/huggingface/alignment-handbook/) : A comprehensive guide related to the alignment and optimization of machine learning models.
- [Lighteval Framework](https://github.com/huggingface/lighteval) : A framework for evaluating machine learning models with a focus on lightweight design.

## Topics

![](topics/Model/SmolLM2)

![](topics/Library/Transformers)

![](topics/Concept/Instruction%20Tuning)

![](topics/Concept/Zero%20shot%20Evaluation)

![](topics/Dataset/FineWeb%20Edu)

![](topics/Tool/TensorBoard)

![](topics/Library/ONNX)