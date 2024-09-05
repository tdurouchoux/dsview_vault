---
already_read: false
link: https://www.rungalileo.io/hallucinationindex
read_priority: 1
source: null
tags:
- Large_Language_Model
- Generative_AI
- Model_evaluation
type: Content
upload_date: '2024-08-08'
---

https://www.rungalileo.io/hallucinationindex
## Summary

The LLM Hallucination Index RAG Special evaluates the performance of 22 leading language models (LLMs) in terms of their adherence to context and the occurrence of hallucinations. The report highlights the growing significance of Retrieval-Augmented Generation (RAG) in AI solutions and the ongoing challenge of hallucinations despite advancements in model size and capabilities.

Key insights include:

1. **Context Length Performance**: Models were tested across short (less than 5k tokens), medium (5k to 25k tokens), and long (40k to 100k tokens) contexts. Results showed that many models performed well with extended context lengths.

2. **Open vs. Closed Source**: Open-source models are closing the performance gap with closed-source models, with notable improvements in hallucination performance.

3. **Model Efficiency**: Smaller models sometimes outperformed larger ones, indicating that design efficiency can be more critical than sheer size.

4. **Top Performers**:
   - **Best Overall**: Claude 3.5 Sonnet, excelling across all context lengths.
   - **Best Cost-Performance**: Gemini 1.5 Flash, offering strong performance at a lower cost.
   - **Best Open-Source**: Qwen2-72B-Instruct, notable for its long context support.

5. **Testing Methodology**: The evaluation involved diverse datasets and a Context Adherence metric to measure factual accuracy and hallucinations.

Overall, the report emphasizes the importance of context length in model performance and the evolving landscape of LLMs, with a focus on balancing performance and cost.
## Links

1. [Context Adherence](https://docs.rungalileo.io/galileo/gen-ai-studio-products/guardrail-store/context-adherence/groundedness) - A detailed explanation of the Context Adherence evaluation metric used to measure factual accuracy and hallucinations in LLMs.
2. [ChainPoll](https://www.rungalileo.io/blog/chainpoll) - An article discussing the ChainPoll prompting technique that aims to improve performance in LLMs, particularly in medium context scenarios.
3. [Github](https://github.com/rungalileo/hallucination-index) - The repository for the Hallucination Index, which includes code and resources related to the evaluation of LLMs.
4. [Together.ai](https://www.together.ai/) - A platform that provides insights and tools for evaluating and improving AI models, relevant for understanding model performance metrics.
5. [LLM Hallucination Index](https://www.rungalileo.io/hallucinationindex) - The main page for the Hallucination Index, offering insights and rankings of various LLMs based on their performance and hallucination rates.
## Topics

- [[topics/Concept/Hallucination Index]]
- [[topics/Concept/Retrieval-Augmented Generation (RAG)]]
- [[topics/Model/Claude 3.5 Sonnet]]
- [[topics/Model/Gemini]]
- [[topics/Model/Qwen2-72B-Instruct]]