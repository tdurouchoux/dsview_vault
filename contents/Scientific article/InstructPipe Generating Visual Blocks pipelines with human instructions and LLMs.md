---
already_read: false
link: https://research.google/blog/instructpipe-generating-visual-blocks-pipelines-with-human-instructions-and-llms/
read_priority: 2
relevance: 0
source: null
tags:
- Large_Language_Model
- AI_agent
- Natural_Language_Processing
type: Content
upload_date: '2025-05-05'
---

https://research.google/blog/instructpipe-generating-visual-blocks-pipelines-with-human-instructions-and-llms/
## Summary

InstructPipe is a research prototype designed to assist users in generating AI pipelines through natural language instructions and large language models (LLMs). It integrates with Visual Blocks, a visual programming framework, to automate the selection and connection of nodes in a pipeline.

The system comprises three main modules:
1. **Node Selector**: Filters relevant nodes based on user instructions.
2. **Code Writer**: Generates pseudocode for the pipeline.
3. **Code Interpreter**: Parses the pseudocode and renders it into a JSON-formatted pipeline within Visual Blocks.

InstructPipe uses a two-stage LLM refinement strategy to generate pseudocode, which is then interpreted into a visual programming pipeline. This approach significantly reduces the number of user interactions required to create a pipeline, as demonstrated in technical and user evaluations.

Key findings from the evaluations include:
- InstructPipe reduces the number of user interactions by 18.9% compared to building pipelines from scratch.
- Users experienced lower workload and faster task completion times when using InstructPipe.
- Qualitative feedback highlighted the system's onboarding support and potential for accessible ML prototyping and education.

The research concludes that InstructPipe automates a significant portion of the pipeline creation process, facilitating human-AI collaboration in visual programming. Future directions involve addressing the challenges of integrating LLMs into visual programming environments and fostering further innovation in this field.
## Links

- [Visual Blocks GitHub Repository](https://github.com/google/visualblocks) : GitHub repository for Visual Blocks, a visual programming framework for ML prototyping.
- [InstructPipe Research Paper](https://research.google/pubs/instructpipe-building-visual-programming-pipelines-with-human-instructions/) : Research paper detailing InstructPipe, an AI assistant for prototyping machine learning pipelines with text instructions.
- [NASA-TLX Wikipedia](https://en.wikipedia.org/wiki/NASA-TLX) : Wikipedia page explaining the NASA-TLX, a tool used to measure workload in the user study.

## Topics

![](topics/Concept/InstructPipe)

![](topics/Concept/Visual%20Blocks%20for%20ML)

![](topics/Concept/Pseudocode)

![](topics/Concept/Directed%20Acyclic%20Graph%20DAG)