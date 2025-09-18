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

The article discusses the advantages of using open source large language models (LLMs) over proprietary ones, focusing on strategies to build AI applications that are cheaper, faster, and better. Key points include:

1. **Proprietary vs. Open Source LLMs**: Proprietary LLMs offer state-of-the-art performance but are expensive, slower, and have rate limits. Open source LLMs are cheaper, faster, and more configurable but have smaller context windows and historically lag in performance.

2. **Requirements of an Effective LLM System**: There are tradeoffs between task performance, throughput, and cost. Open source models can achieve better throughput and cost profiles while maintaining or improving task performance.

3. **Strategies for Open Source LLMs**:
   - **Multi-turn Conversations and Control Flow**: Decompose complex tasks into granular subtasks to improve task performance.
   - **Constrained Decoding**: Useful for structured outputs, increasing throughput and decreasing costs.
   - **Caching, Model Quantisation, and Other Backend Optimisations**: Improve throughput and decrease costs without affecting task performance.
   - **Model Fine-Tuning and Knowledge Distillation**: Improve task performance without impacting inference costs or throughput.
   - **Optimal Model Sizing**: Use the smallest model that can reliably complete the task to increase throughput and decrease costs.

4. **Technical Roadmap**: A logical order for implementing these techniques, considering dependencies and feedback loops for continuous improvement.

5. **Conclusion**: Open source models can outperform proprietary LLMs when engineered to leverage their unique advantages, making them faster, cheaper, and better. The choice depends on the application, budget, and engineering resources.
## Links

- [SGLang](https://lmsys.org/blog/2024-01-17-sglang/?ref=aidancooper.co.uk) : SGLang is a runtime for running LLMs locally. It is a recent player with similar capabilities as vLLM, and an innovative RadixAttention caching approach that claims especially impressive performance.
- [vLLM](https://github.com/vllm-project/vllm?ref=aidancooper.co.uk) : vLLM is a serving framework, boasting various caching mechanisms, parallelisations, kernel optimisations, and model quantisation methods.
- [Constrained Decoding](https://www.aidancooper.co.uk/constrained-decoding/) : Constrained decoding is a powerful technique that can guarantee outputs that conform to the desired structure, drastically improve throughput by accelerating token generation, and reducing the number of tokens that need to be generated.

## Topics

![[topics/Concept/Retrieval Augmented Generation RAG]]

![[topics/Concept/Knowledge Distillation]]

![[topics/Concept/Quantization]]

![[topics/Concept/Tree of Thoughts ToT]]

![[topics/Concept/Chain of Thought Prompting]]

![[topics/Concept/ReAct]]

![[topics/Concept/Parameter Efficient Fine Tuning PEFT]]