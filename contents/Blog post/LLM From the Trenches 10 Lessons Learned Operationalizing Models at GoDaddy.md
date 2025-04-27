---
already_read: true
link: https://www.godaddy.com/resources/news/llm-from-the-trenches-10-lessons-learned-operationalizing-models-at-godaddy
read_priority: 0
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2024-10-07'
---

https://www.godaddy.com/resources/news/llm-from-the-trenches-10-lessons-learned-operationalizing-models-at-godaddy
## Summary

GoDaddy's experience with operationalizing large language models (LLMs) reveals several key lessons:

1. **Prompt Design**: Initial attempts at using a single, comprehensive prompt led to inefficiencies. Transitioning to task-oriented prompts improved conversation management and accuracy.

2. **Structured Outputs**: While structured outputs (e.g., JSON) are useful, they require careful validation to ensure reliability. Implementing functions in models like ChatGPT enhances accuracy, but there can still be significant error rates.

3. **Model Variability**: Prompts are not portable across different models or versions. Continuous tuning is required to optimize performance.

4. **Guardrails**: Implementing safeguards is crucial due to the probabilistic nature of LLM outputs to prevent undesirable actions by the models.

5. **Performance Issues**: LLMs can exhibit slow response times and failures. Basic retry logic and asynchronous communication can mitigate these issues.

6. **Memory Management**: Effective context management for LLMs is challenging but essential. Techniques such as summarization and memory stacks are beneficial.

7. **Adaptive Model Selection**: Switching between models based on reliability and context needs may become essential as LLM implementations evolve.

8. **Retrieval-Augmented Generation (RAG)**: RAG can enhance LLM responses by incorporating external information, but its execution needs to be timely and contextually relevant.

9. **Data Optimization**: Converting datasets into a more useful format for models and employing techniques like Sparse Priming Representations (SPRs) can reduce token usage and improve performance.

10. **Testing**: Continuous testing is critical, as minor prompt changes can significantly affect model performance. Human involvement in testing is necessary to ensure quality.

These insights emphasize the need for careful implementation, ongoing optimization, and rigorous testing when operationalizing LLMs for enhancing user experiences.
## Links

- [LLM Agents and Tools Overview](https://promptengineering.org/what-are-large-language-model-llm-agents/) : An informative overview of Large Language Model Agents and their functionality in conversations.
- [Sparse Priming Representations GitHub Repository](https://github.com/daveshap/SparsePrimingRepresentations) : A GitHub repository detailing techniques for reducing token usage in models through Sparse Priming Representations.
- [Salesforce Multi-Agent Architecture (BOLAA)](https://github.com/salesforce/BOLAA) : A repository that discusses the multi-agent architecture and the controller-delegate pattern relevant for implementing LLMs.
- [LangChain Documentation](https://python.langchain.com/) : Documentation for LangChain, a framework designed for building applications with LLMs, focusing on memory management and context.
- [AI-Powered Social Media Posts](https://www.godaddy.com/resources/news/ai-powered-social-media-posts-enhancing-marketing-with-ai-powered-content-creation) : An article about enhancing marketing through AI-powered content creation, relevant for understanding LLM applications in marketing.

## Topics

![](topics/Concept/Adaptive%20Model%20Selection)

![](topics/Concept/Retrieval%20Augmented%20Generation)

![](topics/Library/LangChain)

![](topics/Concept/Multi%20agent%20Architecture)

![](topics/Concept/Structured%20Outputs%20in%20AI%20Models)

![](topics/Concept/Memory%20Management%20in%20AI%20Systems)

![](topics/Concept/Prompt%20Engineering)