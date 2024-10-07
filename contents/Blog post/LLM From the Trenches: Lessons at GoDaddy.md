---
already_read: true
link: https://www.godaddy.com/resources/news/llm-from-the-trenches-10-lessons-learned-operationalizing-models-at-godaddy#h-1-sometimes-one-prompt-isn-t-enough
read_priority: 0
source: Aucune
tags:
- Large_Language_Model
- AI_regulation
- MlOps
type: Content
upload_date: '2024-10-07'
---

https://www.godaddy.com/resources/news/llm-from-the-trenches-10-lessons-learned-operationalizing-models-at-godaddy#h-1-sometimes-one-prompt-isn-t-enough
## Summary

GoDaddy's experience in operationalizing large language models (LLMs) reveals ten key lessons:

1. **Prompt Complexity**: Initial experiments showed that a single prompt often isn't sufficient. Transitioning to task-oriented prompts improved efficiency and accuracy in complex conversations.

2. **Structured Outputs**: While plain-text responses work well, structured outputs (like JSON) require careful validation to ensure reliability. Adjusting model parameters can enhance output accuracy.

3. **Model-Specific Prompts**: Prompts are not universally applicable across different models or versions. Continuous tuning is necessary to maintain performance.

4. **AI Guardrails**: Implementing controls to prevent LLMs from making critical decisions is essential. This includes checks for sensitive information and deterministic methods for user transfers.

5. **Reliability and Latency**: LLMs can be slow and unreliable. Implementing retry logic and considering asynchronous responses can mitigate these issues.

6. **Memory Management**: Managing context effectively is challenging. Strategies like summarization and dynamic retrieval can help maintain relevant information without excessive costs.

7. **Adaptive Model Selection**: The ability to switch models dynamically based on context and reliability is crucial for maintaining service during outages or high-demand situations.

8. **Effective Use of RAG**: Retrieval-Augmented Generation (RAG) should be implemented thoughtfully, focusing on relevant content after understanding user intent.

9. **Data Optimization for RAG**: Converting datasets into more model-friendly formats can reduce token usage and improve performance.

10. **Continuous Testing**: Testing is labor-intensive but vital. Regular reviews and a multidisciplinary approach can help identify and resolve issues quickly.

Overall, while LLMs offer significant potential for enhancing user experience, careful implementation, ongoing adjustments, and robust testing are critical for success.
## Links

1. [BOLAA paper](https://github.com/salesforce/BOLAA) - A research paper discussing the Multi-Agent architecture for LLMs, which inspired the approach taken at GoDaddy.
2. [LangChain](https://python.langchain.com/) - A framework for developing applications powered by language models, which includes memory management techniques relevant to the challenges discussed.
3. [LLM Agents (with Tools)](https://promptengineering.org/what-are-large-language-model-llm-agents/) - An overview of LLM agents and their capabilities, which relates to the implementation of RAG and task-oriented prompts.
4. [Sparse Priming Representations (SPRs)](https://github.com/daveshap/SparsePrimingRepresentations) - A technique for optimizing data representation for LLMs, which is relevant to the lessons learned about tuning data for RAG.
5. [Example Article](https://github.com/gdcorp-opensource/godaddy.github.io/blob/12aa52476dda5e05a1bcc6e17d383bddafeb99bf/posts/llm-from-trenches/example-article.txt) - An example of how to structure content for better performance in LLM applications, which ties into the discussion on managing structured outputs.
## Topics

- [[topics/Concept/Operationalizing LLMs]]
- [[topics/Concept/Prompt Engineering]]
- [[topics/Concept/Memory Management]]
- [[topics/Concept/Retrieval Augmented Generation (RAG)]]
- [[topics/Concept/Adaptive Model Selection]]