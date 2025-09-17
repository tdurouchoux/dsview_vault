---
already_read: true
link: https://www.godaddy.com/resources/news/llm-from-the-trenches-10-lessons-learned-operationalizing-models-at-godaddy
read_priority: 0
relevance: 0
source: null
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2024-10-07'
---

https://www.godaddy.com/resources/news/llm-from-the-trenches-10-lessons-learned-operationalizing-models-at-godaddy
## Summary

GoDaddy's experience with operationalizing large language models (LLMs) highlights several key lessons:

1. **Prompt Management**: Mega-prompts can become unwieldy. Task-oriented prompts are more efficient for specific tasks, but a balance between mega and task-oriented prompts is often necessary. A multi-prompt architecture using a Controller-Delegate pattern can simplify the code base and enhance capabilities.

2. **Structured Outputs**: Structured outputs like JSON or code should be requested carefully. Validation is crucial, and strategies like minimizing prompt temperature and using advanced models can enhance reliability.

3. **Model-Specific Prompts**: Prompts are not portable across different models or even versions of the same model. Continuous fine-tuning and testing are essential to validate performance.

4. **AI Guardrails**: Implementing guardrails is crucial to manage the probabilistic nature of LLM outputs. Deterministic methods should be used for critical actions, and human intervention should be defaulted when in doubt.

5. **Performance Issues**: Models can be slow and unreliable. Implementing retry logic and considering asynchronous responses can mitigate these issues. Streaming APIs can provide a better user experience.

6. **Memory Management**: Managing context is challenging. Techniques like summarization, entity recognition, and dynamic retrieval can help. For multi-agent architectures, using "stacks" for ephemeral working memory can be beneficial.

7. **Adaptive Model Selection**: Dynamically changing models can address reliability and cost concerns. This approach will become increasingly important as LLM implementations mature.

8. **Effective RAG**: Retrieval-Augmented Generation (RAG) should be used effectively. Dynamic content can aid in customizing prompt behavior, and allowing the model to craft search queries can improve relevancy.

9. **Data Tuning for RAG**: Converting datasets into formats more useful for models, such as using Sparse Priming Representations (SPRs), can improve performance. Document clustering can also reduce duplication and widen the knowledge space.

10. **Testing**: Testing is labor-intensive and more difficult than building an LLM integration. Leveraging LLMs to test other LLMs and building reporting systems for human review are essential. Multidisciplinary review teams can help detect and fix problems quickly.

These insights underscore the importance of careful implementation, continuous fine-tuning, and thorough testing when operationalizing LLMs.
## Links

- [Sparse Priming Representations](https://github.com/daveshap/SparsePrimingRepresentations) : GitHub repository for Sparse Priming Representations (SPRs), a technique to summarize content for better LLM performance.
- [BOLAA](https://github.com/salesforce/BOLAA) : GitHub repository for Salesforce's BOLAA paper, which inspired GoDaddy's multi-agent architecture.
- [LangChain](https://python.langchain.com/) : LangChain library for memory management in LLMs, including techniques like buffers, summarization, and entity recognition.
- [LLM Agents](https://promptengineering.org/what-are-large-language-model-llm-agents/) : Explanation of LLM Agents, which pair prompts with actions (tools) to improve conversation flow.

## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation)

![](topics/Concept/Agentic%20AI)

![](topics/Concept/Sparse%20Priming%20Representations%20SPRs)

![](topics/Concept/Task%20Oriented%20Prompts)

![](topics/Concept/Controller%20Delegate%20Pattern)

![](topics/Concept/Adaptive%20Model%20Selection)