---
already_read: false
link: https://arxiv.org/pdf/2308.09687.pdf
read_priority: 1
source: null
tags:
- Large_Language_Model
- Natural_Language_Processing
- Generative_AI
type: Content
upload_date: '2023-09-14'
---

![](artefacts/2308.09687.pdf)
## Summary

The paper introduces the Graph of Thoughts (GoT) framework, which enhances the prompting capabilities of large language models (LLMs) by modeling the reasoning process as an arbitrary graph. In this framework, "thoughts" are represented as vertices, and dependencies between them are edges, allowing for more complex reasoning patterns compared to previous methods like Chain-of-Thought (CoT) and Tree of Thoughts (ToT).

Key points include:

1. **Graph Structure**: GoT allows for arbitrary graph structures, enabling the combination of multiple thoughts and the use of feedback loops to refine reasoning.

2. **Performance Improvements**: GoT demonstrates significant improvements in task performance, such as a 62% increase in sorting quality over ToT while reducing costs by over 31%.

3. **Extensibility**: The framework is designed to be modular, allowing for the integration of new thought transformations and the use of various LLMs.

4. **Use Cases**: The paper illustrates several applications of GoT, including sorting, keyword counting, set operations, and document merging, showcasing its versatility and effectiveness.

5. **Evaluation Metrics**: A new metric, "volume of a thought," is proposed to assess the potential contributions of thoughts in the graph, highlighting GoT's ability to support richer thought transformations.

6. **System Architecture**: The architecture consists of modules for prompting, parsing, scoring, and controlling the reasoning process, facilitating the implementation of complex tasks.

Overall, GoT represents a significant advancement in the field of prompt engineering for LLMs, aligning more closely with human-like reasoning processes and offering a robust framework for tackling elaborate problems.
## Topics

![](topics/Concept/Graph%20of%20Thoughts)

![](topics/Concept/Prompt%20Engineering)

![](topics/Concept/Thought%20Transformations)

![](topics/Concept/Scoring%20and%20Ranking)

![](topics/Product/Graph%20of%20Thoughts%20GitHub%20Repository)