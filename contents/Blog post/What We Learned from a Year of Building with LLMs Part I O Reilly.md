---
already_read: false
link: https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2024-06-05'
---

https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/
## Summary

Large language models (LLMs) have significantly improved over the past year, becoming viable for real-world applications. This growth is expected to fuel substantial investment in AI. The authors present practical insights gained from building LLM applications, categorized into three sections: tactical, operational, and strategic, with the first part focusing on tactical aspects.

Key takeaways include:

1. **Effective Prompting**:
   - Understand the fine balance of prompt importance; simple prompts often lead to better outcomes.
   - Use n-shot prompting and chain-of-thought techniques to improve model responses.
   - Provide relevant resources to ground responses, especially through retrieval-augmented generation (RAG).

2. **Designing Inputs and Outputs**:
   - Structure prompts to improve model understanding and the reliability of outputs for integration into downstream systems.
   - Simplify prompts to ensure they perform specific tasks effectively.

3. **Information Retrieval**:
   - RAG is more effective than fine-tuning for incorporating new knowledge, emphasizing relevance and conciseness in retrieved documents.
   - A hybrid approach using both keyword and embedding-based methods often yields better results.

4. **Optimization of Workflows**:
   - Break down complex tasks into smaller, manageable steps (multi-turn workflows) to achieve accuracy improvements.
   - Employ deterministic processes to enhance reliability in agent interactions.

5. **Outcomes and Evaluation**:
   - Implement systematic evaluation strategies through unit tests and LLM-as-Judge methodologies.
   - Focus on defining practical and binary evaluation criteria to enhance the reliability of output assessments.

6. **Handling Output Challenges**:
   - Address potential issues like hallucinations with both proactive prompt design and reactive guardrails to filter undesirable outputs.

The article aims to equip practitioners, irrespective of their machine learning background, with the knowledge to build successful LLM applications and navigate the challenges that arise in their deployment and evaluation. Further sections on operational and strategic insights are to follow.
## Links

- [Fine-tuning Techniques for LLMs](https://eugeneyan.com/writing/finetuning/) : An insightful guide on the best practices for fine-tuning large language models (LLMs).
- [Hamel Husain's Evaluation Strategies for LLMs](https://hamel.dev/blog/posts/evals/#automated-evaluation-w-llms) : A blog post discussing automated evaluation methods for LLMs and associated challenges.
- [Mean Reciprocal Rank (MRR) Overview](https://en.wikipedia.org/wiki/Mean_reciprocal_rank) : Wikipedia page detailing the Mean Reciprocal Rank, a measure used for evaluating the effectiveness of search algorithms.
- [Execution-Based Evaluation for Open-Domain Code Generation](https://www.semanticscholar.org/paper/Execution-Based-Evaluation-for-Open-Domain-Code-Wang-Zhou/1bed34f2c23b97fd18de359cf62cd92b3ba612c3) : A research paper that explores execution-based evaluation methods specifically for code generation tasks.
- [Discounted Cumulative Gain (DCG) Explanation](https://en.wikipedia.org/wiki/Discounted_cumulative_gain) : A Wikipedia article that provides an explanation of Discounted Cumulative Gain, a measure for ranking relevant documents.

## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Chain%20of%20Thought%20Prompting)

![](topics/Concept/Human%20in%20the%20loop%20Workflows)

![](topics/Concept/Structured%20Input%20and%20Output%20Design)

![](topics/Concept/Deterministic%20Workflows)