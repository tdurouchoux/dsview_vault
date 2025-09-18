---
already_read: false
link: https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2024-06-05'
---

https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/
## Summary

The article discusses key lessons and methodologies for building effective products using large language models (LLMs). It is organized into three sections: tactical, operational, and strategic, with this part focusing on the tactical aspects. The authors, who have diverse backgrounds and experiences in building real-world applications with LLMs, share their insights and best practices.

**Tactical Lessons:**

1. **Prompting:**
   - Start with fundamental prompting techniques like n-shot prompts, chain-of-thought, and providing relevant resources.
   - Structure inputs and outputs to help models understand tasks better and integrate outputs downstream.
   - Keep prompts small and focused on one task to avoid complexity and improve performance.

2. **Information Retrieval/RAG (Retrieval-Augmented Generation):**
   - RAG is effective for grounding LLMs and improving output quality.
   - Quality of RAG output depends on the relevance, density, and detail of retrieved documents.
   - Keyword search should not be overlooked and can be used in hybrid search systems.
   - RAG is preferred over fine-tuning for incorporating new knowledge due to its ease of use and cost-effectiveness.
   - Long-context models won't make RAG obsolete as retrieval and ranking are still necessary.

3. **Tuning and Optimizing Workflows:**
   - Decompose complex tasks into simpler, step-by-step flows to improve performance.
   - Prioritize deterministic workflows for reliability and easier debugging.
   - Use techniques like caching to save costs and reduce latency.
   - Fine-tune models only when prompting falls short, considering the significant costs involved.

4. **Evaluation & Monitoring:**
   - Create assertion-based unit tests from real input/output samples.
   - LLM-as-Judge can be useful but is not a silver bullet; use it for pairwise comparisons and control for biases.
   - Use the "intern test" to evaluate generations and identify areas for improvement.
   - Simplify annotation tasks to binary classifications or pairwise comparisons for more reliable data.
   - Implement guardrails to catch inappropriate or harmful content and use reference-free evals interchangeably with guardrails.
   - Address hallucinations through prompt engineering and factual inconsistency guardrails.

The authors emphasize the importance of rigorous evaluation and monitoring, as well as the need for structured, deterministic approaches to building reliable LLM applications. They also highlight the challenges and costs associated with fine-tuning and the benefits of using RAG for incorporating new knowledge.
## Links

- [Eugene Yan's Personal Website](https://eugeneyan.com/) : Eugene Yan's personal website, where he writes and speaks about machine learning, recommendation systems, LLMs, and engineering.
- [Hamel Husain's Profile](https://www.oreilly.com/people/hamel-husain/) : Hamel Husain's profile on O'Reilly, highlighting his expertise and contributions in machine learning and LLMs.
- [Labeling Guidelines by Eugene Yan](https://eugeneyan.com/writing/labeling-guidelines/) : Guidelines for creating effective labeling tasks for machine learning models, by Eugene Yan.
- [Introducing Query Assistant by Honeycomb](https://www.honeycomb.io/blog/introducing-query-assistant) : Introduction to Honeycomb's Natural Language Query Assistant, which uses fine-tuning to improve output quality.
- [Shortwave's RAG Pipeline](https://www.shortwave.com/blog/deep-dive-into-worlds-smartest-email-ai/) : A deep dive into Shortwave's RAG pipeline, including query rewriting, keyword + embedding retrieval, and ranking.

## Topics

![[topics/Concept/Retrieval Augmented Generation RAG)]]

![[topics/Concept/Prompt Engineering)]]

![[topics/Concept/Fine tuning)]]

![[topics/Concept/Caching)]]

![[topics/Concept/Flow Engineering)]]

![[topics/Concept/Evaluation and Monitoring)]]