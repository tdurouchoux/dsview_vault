---
already_read: false
link: https://arxiv.org/pdf/2308.09687.pdf
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2023-09-14'
---

![](artefacts/2308.09687.pdf)
## Summary

Graph of Thoughts (GoT) introduces a new prompting framework for large language models (LLMs) that enhances problem-solving abilities by modeling LLM outputs as a graph structure. Key features include:

1. **Graph Abstraction**: Thoughts are represented as vertices in a graph, while edges denote dependencies. This allows for more dynamic and flexible reasoning compared to the rigid structures imposed by previous models such as Chain-of-Thought (CoT) and Tree of Thoughts (ToT).

2. **Enhanced Synergy**: GoT enables the combination of multiple thoughts to improve overall reasoning quality and efficiency, facilitating feedback loops and iterative enhancement.

3. **Performance Improvements**: In empirical evaluations, GoT has shown a 62% improvement in sorting task quality over ToT and more than 31% reduction in costs.

4. **Flexibility and Extensibility**: The framework is designed to incorporate new thought transformations easily, making it adaptable for various tasks, such as document merging and keyword counting.

5. **Novel Metrics**: GoT establishes a new metric called "volume of a thought," measuring the potential contributions from preceding thoughts in the graph, enhancing the understanding of thought processes in LLMs.

The architecture includes modules for prompt preparation, thought scoring, and control, allowing for systematic exploration of thought transformations and their implications for LLM reasoning.

Use cases for GoT include tasks like sorting, set operations, keyword counting, and document merging, with detailed descriptions of configurations and evaluations showcasing its effectiveness compared to traditional methods. Overall, GoT represents a significant step forward in making LLMs more capable of handling complex reasoning tasks.
## Topics

![](topics/Concept/Graph%20of%20Thoughts)

![](topics/Concept/Prompt%20Engineering)

![](topics/Concept/Self%20Consistency%20with%20Chain%20of%20Thought%20CoT%20SC)

![](topics/Concept/Tree%20of%20Thoughts%20ToT)

![](topics/Dataset/Graph%20based%20Metrics%20for%20Prompt%20Evaluation)