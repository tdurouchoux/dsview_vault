---
already_read: false
link: https://www.aidancooper.co.uk/how-to-beat-proprietary-llms/
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2024-05-05'
---

https://www.aidancooper.co.uk/how-to-beat-proprietary-llms/
## Summary

The article discusses the advantages of using open source large language models (LLMs) over proprietary ones, focusing on strategies to make open source models more effective. Key points include:

1. **Proprietary vs. Open Source LLMs**: Proprietary LLMs offer state-of-the-art performance but are expensive, slower, and have rate limits. Open source LLMs are cheaper, faster, and more configurable but historically lag in performance.

2. **Key Strategies for Open Source LLMs**:
   - **Multi-turn Conversations and Control Flow**: Break down complex tasks into subtasks to improve performance.
   - **Constrained Decoding**: Ensures structured outputs, improves throughput, and reduces costs.
   - **Caching and Optimisations**: Techniques like caching and model quantisation increase throughput and reduce costs.
   - **Model Fine-Tuning and Knowledge Distillation**: Enhances task performance without affecting inference costs or throughput.
   - **Optimal Model Sizing**: Use the smallest model that can reliably complete the task to balance performance, cost, and throughput.

3. **Technical Roadmap**: A dependency map outlines the order of implementing these techniques, emphasizing the importance of aligning them to prevent dysfunction.

4. **Conclusion**: Open source models can outperform proprietary LLMs in speed, cost, and performance by leveraging sophisticated system design and appropriate tradeoffs. The choice between open source and proprietary models depends on the application, budget, and engineering resources.

The article also mentions related content, such as benchmarks for evaluating LLM chess reasoning and the convergence of proprietary and open source LLMs.
## Links

- [Constrained Decoding](https://www.aidancooper.co.uk/constrained-decoding/) : A guide to structured generation using constrained decoding, explaining the how, why, power, and pitfalls of constraining generative language model outputs.
- [Hugging Face Quantization](https://huggingface.co/docs/optimum/en/concept_guides/quantization) : Documentation on quantization techniques for optimizing language models, provided by Hugging Face.
- [SGLang GitHub](https://github.com/sgl-project/sglang) : The GitHub repository for SGLang, a runtime for serving large language models with high throughput and low latency.

## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Chain%20of%20Thought%20CoT)

![](topics/Concept/ReAct)

![](topics/Concept/Constrained%20Decoding)

![](topics/Concept/Model%20Quantization)

![](topics/Concept/Parameter%20Efficient%20Fine%20Tuning%20PEFT)

![](topics/Concept/Tree%20of%20Thoughts%20ToT)

![](topics/Concept/Knowledge%20Distillation)