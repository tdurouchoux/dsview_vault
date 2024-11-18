---
already_read: false
link: https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/?utm_source=substack&utm_medium=email
read_priority: 1
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2024-06-05'
---

https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/?utm_source=substack&utm_medium=email
## Summary

Over the past year, the authors have explored the practicalities of building applications with large language models (LLMs), identifying key lessons and methodologies that can enhance product development. The content is structured into three sections: tactical, operational, and strategic, with Part I focusing on tactical aspects.

Key takeaways include:

1. **Prompting Techniques**: Effective prompting is crucial. Techniques such as n-shot prompting, chain-of-thought (CoT), and providing relevant resources can significantly improve model performance. It's important to structure inputs and outputs clearly and keep prompts simple to avoid complexity.

2. **Retrieval-Augmented Generation (RAG)**: RAG enhances LLMs by grounding them in relevant documents, improving output quality. The effectiveness of RAG depends on the relevance and density of retrieved documents, and a hybrid approach combining keyword and embedding-based searches is recommended.

3. **Workflow Optimization**: Breaking down complex tasks into smaller, manageable steps can lead to better results. Deterministic workflows are preferred for reliability, and caching can reduce latency and costs.

4. **Evaluation and Monitoring**: Rigorous evaluation is essential. Techniques like assertion-based unit tests and LLM-as-Judge can help assess model outputs. However, overemphasis on specific evaluation metrics can lead to unintended consequences.

5. **Addressing Hallucinations**: Hallucinations remain a challenge, necessitating a combination of prompt engineering and factual inconsistency guardrails to mitigate their impact.

Overall, the authors emphasize the importance of practical experience and iterative learning in successfully leveraging LLMs for real-world applications.
## Links

1. [Execution-Based Evaluation for Open-Domain Code Generation](https://www.semanticscholar.org/paper/Execution-Based-Evaluation-for-Open-Domain-Code-Wang-Zhou/1bed34f2c23b97fd18de359cf62cd92b3ba612c3) - A research paper discussing methods for evaluating code generation models based on execution results.
2. [Mean Reciprocal Rank](https://en.wikipedia.org/wiki/Mean_reciprocal_rank) - A metric used to evaluate the effectiveness of information retrieval systems, relevant for assessing LLM performance in retrieval tasks.
3. [Automated Evaluation with LLMs](https://hamel.dev/blog/posts/evals/#automated-evaluation-w-llms) - A blog post detailing strategies for automating the evaluation of LLM outputs.
4. [Labeling Guidelines](https://eugeneyan.com/writing/labeling-guidelines/) - A resource providing guidelines for creating effective labeling systems for model evaluation.
5. [Hybrid Search Techniques](https://www.shortwave.com/blog/deep-dive-into-worlds-smartest-email-ai/) - An article exploring the combination of keyword and embedding-based search methods, relevant for improving LLM retrieval capabilities.
## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Prompt%20Engineering)

![](topics/Concept/Human%20in%20the%20Loop%20Workflows)

![](topics/Concept/Evaluation%20Strategies)

![](topics/Concept/Deterministic%20Workflows)