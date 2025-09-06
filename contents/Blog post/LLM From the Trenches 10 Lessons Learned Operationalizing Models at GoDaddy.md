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

GoDaddy's experience with operationalizing large language models (LLMs) has yielded several key lessons:

1. **Prompt Management**: Mega-prompts can become unwieldy. Task-oriented prompts are more efficient for complex conversations, but a balance between mega and task-oriented prompts is often necessary. A multi-prompt architecture using a controller-delegate pattern can simplify the codebase and enhance capabilities.

2. **Structured Outputs**: Structured outputs like JSON or code should be requested carefully. Validation is crucial, and strategies like minimizing prompt temperature and using more advanced models can enhance reliability.

3. **Model-Specific Prompts**: Prompts are not portable across different models or even different versions of the same model. Continuous fine-tuning and testing are essential to ensure performance.

4. **AI Guardrails**: Implementing guardrails is critical to manage the probabilistic nature of LLM outputs. Deterministic methods should be used for sensitive actions, and human intervention should be defaulted when in doubt.

5. **Performance Issues**: LLMs can be slow and unreliable. Implementing retry logic and considering asynchronous responses can mitigate these issues. Streaming APIs can provide a better user experience.

6. **Memory Management**: Managing context in LLMs is challenging. Techniques like summarization, entity recognition, and dynamic retrieval can be effective. For multi-agent architectures, using "stacks" for ephemeral working memory can be beneficial.

7. **Adaptive Model Selection**: Dynamically changing models to address reliability and cost concerns is a future trend. This approach can be particularly useful during outages or when dealing with dissatisfied customers.

8. **Effective RAG**: Retrieval-Augmented Generation (RAG) should be used effectively. Dynamic content can aid in customizing prompt behavior, and allowing the model to craft search queries can improve relevancy.

9. **Data Tuning for RAG**: Converting datasets into formats more useful for models, such as using Sparse Priming Representations (SPRs), can improve performance. Document clustering can also reduce duplication and widen the knowledge space.

10. **Testing**: Testing is labor-intensive and more difficult than building LLM integrations. Leveraging LLMs to test other LLMs and building reporting systems for human review are essential. Multidisciplinary review teams can help detect and fix problems quickly.

These insights highlight the importance of careful implementation, continuous fine-tuning, and thorough testing when operationalizing LLMs.
## Links

- [Sparse Priming Representations](https://github.com/daveshap/SparsePrimingRepresentations) : GitHub repository for Sparse Priming Representations, a technique used to summarize content for better LLM performance.
- [LangChain Library](https://python.langchain.com/) : LangChain library, which includes various techniques for memory management in conversational AI assistants.
- [BOLAA Paper](https://github.com/salesforce/BOLAA) : GitHub repository for the BOLAA paper by Salesforce, which inspired GoDaddy's multi-prompt architecture.

## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Multi%20Agent%20Architecture)

![](topics/Concept/Sparse%20Priming%20Representations%20SPRs)

![](topics/Concept/Adaptive%20Model%20Selection)

![](topics/Concept/Task%20Oriented%20Prompts)