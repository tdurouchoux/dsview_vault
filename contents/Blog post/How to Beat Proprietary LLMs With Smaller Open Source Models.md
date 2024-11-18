---
already_read: false
link: https://www.aidancooper.co.uk/how-to-beat-proprietary-llms/?utm_source=substack&utm_medium=email
read_priority: 1
source: null
tags:
- Large_Language_Model
- Generative_AI
- AI_regulation
type: Content
upload_date: '2024-05-05'
---

https://www.aidancooper.co.uk/how-to-beat-proprietary-llms/?utm_source=substack&utm_medium=email
## Summary

The article discusses the advantages of using smaller open-source language models (LLMs) over proprietary models like GPT-4 and Gemini for AI applications. Key points include:

- **Comparison of LLMs**: Proprietary models offer state-of-the-art performance but are costly and have limitations in throughput and latency. Open-source models, while potentially less capable, provide greater flexibility, lower costs, and faster response times when properly utilized.

- **Effective LLM System Design**: Successful systems must balance task performance, throughput, and cost. Open-source models allow for more control and optimization strategies that can enhance these aspects.

- **Strategies for Open Source Models**:
  - **Multi-turn Conversations**: Breaking tasks into smaller subtasks can improve performance without overwhelming the model.
  - **Constrained Decoding**: This technique enhances throughput and task performance by ensuring structured outputs, which is not feasible with proprietary models.
  - **Caching and Backend Optimizations**: Implementing caching strategies and model quantization can significantly improve system efficiency.
  - **Fine-Tuning and Knowledge Distillation**: Open-source models allow for extensive fine-tuning, which can enhance task performance without increasing costs.
  - **Optimal Model Sizing**: Selecting the smallest model that meets task requirements can improve throughput and reduce costs.

- **Technical Roadmap**: The article outlines a logical order for implementing these strategies, emphasizing the importance of aligning techniques to avoid dysfunction.

In conclusion, open-source models can outperform proprietary ones in speed, cost, and performance when systems are designed to leverage their unique advantages.
## Links

1. [A Guide to Structured Outputs Using Constrained Decoding](https://www.aidancooper.co.uk/constrained-decoding/) - An article explaining the techniques and benefits of constrained decoding for generating structured outputs with language models.
2. [Using and Fine-tuning Pretrained Transformers](https://magazine.sebastianraschka.com/p/using-and-finetuning-pretrained-transformers?ref=aidancooper.co.uk) - A primer on fine-tuning methods for pretrained transformer models, which is crucial for optimizing task performance.
3. [Hugging Face - Model Quantization](https://huggingface.co/docs/optimum/en/concept_guides/quantization?ref=aidancooper.co.uk) - Documentation on model quantization techniques that can help reduce model size and improve inference speed without significantly compromising performance.
4. [SGLang GitHub Repository](https://github.com/sgl-project/sglang?tab=readme-ov-file&ref=aidancooper.co.uk#control-flow) - A repository for SGLang, a framework that offers various optimizations for serving language models, including caching and parallelization techniques.
5. [Hugging Face - PEFT Documentation](https://huggingface.co/docs/peft/en/index?ref=aidancooper.co.uk) - Documentation on Parameter-Efficient Fine-Tuning (PEFT) techniques, which are essential for adapting models to specific tasks efficiently.
## Topics

![](topics/Concept/Open%20Source%20LLMs)

![](topics/Concept/Proprietary%20LLMs)

![](topics/Concept/Constrained%20Decoding)

![](topics/Concept/Model%20Fine%20Tuning)

![](topics/Product/vLLM)