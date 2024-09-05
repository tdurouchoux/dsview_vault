---
already_read: false
link: https://arxiv.org/pdf/2308.09687.pdf
read_priority: 1
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2023-09-14'
---

![](artefacts/2308.09687.pdf)
## Summary

The paper introduces the Graph of Thoughts (GoT) framework, which enhances the prompting capabilities of large language models (LLMs) by modeling the reasoning process as an arbitrary graph. In this framework, "thoughts" are represented as vertices, and dependencies between them are edges, allowing for more complex and synergistic reasoning compared to previous methods like Chain-of-Thought (CoT) and Tree of Thoughts (ToT).

Key points include:

1. **Graph Structure**: GoT allows for arbitrary graph structures, enabling the combination of multiple thoughts and the use of feedback loops to refine reasoning.

2. **Performance Improvements**: GoT demonstrates significant improvements in task performance, such as a 62% increase in sorting quality over ToT while reducing costs by over 31%.

3. **Extensibility**: The framework is designed to be modular and extensible, allowing for the integration of new thought transformations and prompting strategies.

4. **Use Cases**: The paper illustrates several applications of GoT, including sorting, keyword counting, set operations, and document merging, showcasing its versatility and effectiveness.

5. **Evaluation Metrics**: A new metric, "volume of a thought," is proposed to assess the potential contributions of thoughts in the graph, highlighting GoT's ability to maintain larger volumes of information compared to other prompting schemes.

6. **System Architecture**: The architecture consists of modules for prompting, parsing, scoring, and controlling the reasoning process, facilitating the implementation of various prompting strategies.

Overall, GoT represents a significant advancement in the way LLMs can be prompted to solve complex problems, aligning more closely with human-like reasoning processes.
## Topics

- [[topics/Concept/Graph of Thoughts (GoT)]]
- [[topics/Concept/Prompt Engineering]]
- [[topics/Concept/Thought Transformations]]
- [[topics/Concept/Scoring and Ranking]]
- [[topics/Concept/Modular Architecture and RAG]]