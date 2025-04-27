---
already_read: false
link: https://www.anthropic.com/engineering/building-effective-agents
read_priority: 4
relevance: 0
source: Blef
tags:
- Large_Language_Model
type: Content
upload_date: '2025-03-09'
---

https://www.anthropic.com/engineering/building-effective-agents
## Summary

The document discusses building effective AI agents, particularly applying large language models (LLMs) for various applications. Key takeaways include:

1. **Simplicity Over Complexity**: Successful agent implementations often leverage simple, composable patterns rather than complex frameworks, primarily when scalability and flexibility are essential.

2. **Defining Agents**: "Agents" are distinguished from "workflows." Agents dynamically direct their actions using LLMs, while workflows rely on predefined paths. Both can be useful; choosing between them depends on the required flexibility versus predictability.

3. **Use of Frameworks**: Various frameworks exist to aid agent development (e.g., LangGraph, Rivet). However, starting with direct LLM APIs can minimize unnecessary complexity and enhance debugging clarity.

4. **Agentic Patterns**:
   - **Augmented LLMs**: Basic building blocks enhanced with retrieval, tools, and memory.
   - **Prompt Chaining**: Breaks tasks into sequential LLM calls to improve task accuracy.
   - **Routing**: Directs input to specialized tasks based on classification.
   - **Parallelization**: Handles tasks simultaneously for improved efficiency and diverse outputs.
   - **Orchestrator-Workers**: Dynamically breaks down tasks and assigns them to LLMs.
   - **Evaluator-Optimizer**: Utilizes one LLM for generation and another for evaluation and refinement.

5. **Autonomous Agents**: These can handle open-ended tasks needing iterative steps; however, they require careful design to manage costs and error compounding effectively.

6. **Best Practices**: Maintain simplicity, prioritize transparency, and ensure thorough documentation and testing in tool development.

7. **Promising Areas**: Agents have shown value in customer support and coding tasks, where feedback loops and measurable success criteria exist.

In summary, the effective implementation of AI agents relies on understanding specific use cases, leveraging simple patterns, and incorporating user feedback, all while being mindful of complexity and transparency in design.
## Links

- [Amazon Bedrock AI Agent Framework](https://aws.amazon.com/bedrock/agents/) : This link provides information about Amazon Bedrock's AI Agent framework, which simplifies the development of agentic systems.
- [LangGraph from LangChain](https://langchain-ai.github.io/langgraph/) : LangGraph is a framework from LangChain designed for building agentic systems, offering compositional patterns for developers.
- [Anthropic Cookbook on Agent Patterns](https://github.com/anthropics/anthropic-cookbook/tree/main/patterns/agents) : This GitHub repository contains practical patterns for building agents, featuring examples and implementations tailored for LLMs.
- [Model Context Protocol](https://modelcontextprotocol.io/tutorials/building-a-client#building-mcp-clients) : This tutorial on Model Context Protocol outlines how to build clients that integrate with a growing ecosystem of third-party tools for LLMs.
- [Vellum: GUI Tool for Workflows](https://www.vellum.ai/) : Vellum is a drag-and-drop GUI tool for building and testing complex workflows, particularly for LLM applications.

## Topics

![](topics/Concept/Agentic%20Systems)

![](topics/Concept/Prompt%20Chaining)

![](topics/Concept/Routing)

![](topics/Concept/Parallel%20Computing)

![](topics/Concept/Evaluator%20Optimizer%20Workflow)

![](topics/Library/LangChain)

![](topics/Library/Rivet)

![](topics/Library/Vellum)

![](topics/Library/Amazon%20Bedrock)