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

The article discusses key lessons and methodologies for building effective products with large language models (LLMs). It is organized into three sections: tactical, operational, and strategic, with the first part focusing on tactical aspects. The authors, who have diverse backgrounds and experiences in building real-world applications with LLMs, share their insights and best practices.

**Tactical Lessons:**

1. **Prompting:**
   - Start with fundamental prompting techniques like n-shot prompts, chain-of-thought, and providing relevant resources.
   - Structure inputs and outputs to help models understand tasks better and integrate outputs downstream.
   - Keep prompts small and focused on one task to avoid complexity and improve performance.

2. **Information Retrieval/RAG (Retrieval-Augmented Generation):**
   - RAG's effectiveness depends on the relevance, density, and detail of retrieved documents.
   - Use keyword search as a baseline and consider hybrid search for better results.
   - Prefer RAG over fine-tuning for incorporating new knowledge due to its ease of updates and control.
   - Long-context models won't make RAG obsolete as retrieval and ranking are still necessary.

3. **Tuning and Optimizing Workflows:**
   - Decompose complex tasks into smaller, step-by-step flows for better results.
   - Prioritize deterministic workflows for reliability and easier debugging.
   - Use techniques like caching to save costs and reduce latency.
   - Fine-tune models when prompt engineering falls short, but consider the costs and benefits.

4. **Evaluation & Monitoring:**
   - Create assertion-based unit tests from real input/output samples.
   - Use LLM-as-Judge for evaluating outputs, but be aware of its limitations.
   - Simplify annotation tasks to binary classifications or pairwise comparisons for better results.
   - Use guardrails to catch inappropriate or harmful content and consider them interchangeably with reference-free evals.
   - Address hallucinations through prompt engineering and factual inconsistency guardrails.

The authors emphasize the importance of rigorous evaluation and monitoring, as well as the need for structured, deterministic approaches to build reliable LLM applications. They also highlight the value of community engagement and sharing lessons learned to advance the field.
## Links

- [ApplyingML](https://applyingml.com/) : Eugene Yan's personal website and blog, focusing on machine learning, recommendation systems, and LLMs. Provides insights and practical advice on applying machine learning techniques.
- [Honeycomb Query Assistant](https://www.honeycomb.io/blog/introducing-query-assistant) : Introduction to Honeycomb's Natural Language Query Assistant, which uses fine-tuning to improve the syntax and rules of a domain-specific language.
- [Outlines GitHub](https://github.com/outlines-dev/outlines) : GitHub repository for Outlines, a tool for structured output in LLM applications, useful for integrating structured data into downstream systems.
- [Hamel Husain's Consulting](https://hamel.dev/hire.html) : Hamel Husain's consulting services for operationalizing Large Language Models (LLMs) and accelerating AI product development.
- [Eugene Yan's Labeling Guidelines](https://eugeneyan.com/writing/labeling-guidelines/) : Guidelines for creating effective labeling tasks for machine learning models, focusing on binary classifications and pairwise comparisons to reduce cognitive burden on annotators.

## Topics

![](topics/Concept/Prompt%20Engineering)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Flow%20Engineering)

![](topics/Concept/Evaluation%20and%20Monitoring)

![](topics/Concept/LLM%20as%20Judge)

![](topics/Concept/Fine%20tuning)