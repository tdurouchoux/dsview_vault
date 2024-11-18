---
already_read: true
link: https://www.godaddy.com/resources/news/llm-from-the-trenches-10-lessons-learned-operationalizing-models-at-godaddy#h-1-sometimes-one-prompt-isn-t-enough
read_priority: 0
source: null
tags:
- Large_Language_Model
- AI_regulation
- Model_evaluation
- MlOps
type: Content
upload_date: '2024-10-07'
---

https://www.godaddy.com/resources/news/llm-from-the-trenches-10-lessons-learned-operationalizing-models-at-godaddy#h-1-sometimes-one-prompt-isn-t-enough
## Summary

GoDaddy's experience in operationalizing large language models (LLMs) reveals ten key lessons:

1. **Prompt Complexity**: Initial experiments showed that a single prompt often isn't sufficient. Transitioning to task-oriented prompts improved efficiency and accuracy in complex conversations.

2. **Structured Outputs**: While plain-text responses are effective, structured outputs (like JSON) require careful validation to ensure reliability. Adjusting prompt temperature and using advanced models can enhance accuracy.

3. **Model-Specific Prompts**: Prompts are not universally applicable across different models or versions. Continuous tuning is necessary to maintain performance.

4. **AI Guardrails**: Implementing controls to prevent LLMs from making critical decisions autonomously is essential to avoid user frustration and potential errors.

5. **Reliability and Latency**: LLMs can be slow and unreliable, necessitating strategies like retry logic and asynchronous responses to improve user experience.

6. **Memory Management**: Managing context effectively is challenging. Techniques like summarization and dynamic retrieval can help optimize memory usage.

7. **Adaptive Model Selection**: The ability to switch models dynamically based on context and reliability needs is crucial for maintaining service quality.

8. **Effective Use of RAG**: Retrieval-Augmented Generation (RAG) should be implemented thoughtfully, focusing on relevant content after understanding user intent.

9. **Data Optimization for RAG**: Converting datasets into more useful formats can reduce token usage and improve model performance.

10. **Continuous Testing**: Rigorous testing is vital, as minor prompt changes can significantly impact performance. A multidisciplinary review team can help identify and resolve issues quickly.

Overall, while LLMs offer significant potential for enhancing user experience, careful implementation, ongoing adjustments, and thorough testing are critical for success.
## Links

1. [Sparse Priming Representations](https://github.com/daveshap/SparsePrimingRepresentations) - A GitHub repository discussing techniques for optimizing datasets for models, which can enhance performance in LLM applications.
2. [Salesforce BOLAA Paper](https://github.com/salesforce/BOLAA) - A research paper that explores multi-agent architectures, relevant to the discussion of prompt architecture in LLMs.
3. [LangChain Documentation](https://python.langchain.com/) - A resource for understanding memory management techniques in LLMs, including various strategies for context handling.
4. [Prompt Engineering for LLM Agents](https://promptengineering.org/what-are-large-language-model-llm-agents/) - An article that explains the concept of LLM agents and their application in conversational AI, which aligns with the lessons learned in the source.
5. [Testing LLM Integrations](https://github.com/gdcorp-opensource/godaddy.github.io/blob/12aa52476dda5e05a1bcc6e17d383bddafeb99bf/posts/llm-from-trenches/README.md#10-test-test-test) - A section from the source discussing the importance of testing in LLM implementations, highlighting the challenges and strategies involved.
## Topics

![](topics/Concept/Operationalizing%20LLMs)

![](topics/Concept/Prompt%20Engineering)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Multi%20Agent%20Architecture)

![](topics/Library/LangChain)