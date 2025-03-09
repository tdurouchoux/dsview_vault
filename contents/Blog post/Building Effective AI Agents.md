---
link: https://www.anthropic.com/engineering/building-effective-agents?ref=blef.fr
tags:
- Large_Language_Model
- MlOps
- AI_regulation
type: Content
upload_date: '2025-03-09'
---

https://www.anthropic.com/engineering/building-effective-agents?ref=blef.fr
## Summary

The content discusses the development of effective AI agents, particularly using large language models (LLMs). Key points include:

- **Simplicity Over Complexity**: Successful implementations favor simple, composable patterns rather than complex frameworks. Developers are encouraged to start with basic LLM APIs and only add complexity when necessary.

- **Definitions of Agents**: Agents can be fully autonomous systems or prescriptive implementations. The distinction is made between workflows (predefined code paths) and agents (dynamic decision-making).

- **When to Use Agents**: Agents are beneficial for open-ended problems requiring flexibility, while workflows are better for well-defined tasks. The trade-offs between latency, cost, and performance should be considered.

- **Frameworks**: Various frameworks exist to simplify agent implementation, but they can add unnecessary complexity. Understanding the underlying code is crucial to avoid errors.

- **Building Blocks**: The augmented LLM is the foundational element, enhanced with retrieval, tools, and memory. Key workflows include:
  - **Prompt Chaining**: Decomposes tasks into sequential steps.
  - **Routing**: Directs inputs to specialized tasks.
  - **Parallelization**: Executes tasks simultaneously for efficiency.
  - **Orchestrator-Workers**: Dynamically breaks down tasks and delegates them.
  - **Evaluator-Optimizer**: Iteratively refines outputs based on feedback.

- **Agents in Practice**: Two promising applications are customer support and coding agents, where agents can handle complex tasks with clear success criteria and feedback loops.

- **Best Practices**: Maintain simplicity, prioritize transparency, and ensure thorough documentation of tools. Testing in controlled environments is recommended to mitigate risks.

Overall, the emphasis is on building effective agents through careful design, iterative improvement, and a focus on user needs.
## Links

1. [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook/tree/main/patterns/agents) - A collection of patterns and examples for building agents using LLMs.
2. [Model Context Protocol](https://modelcontextprotocol.io/tutorials/building-a-client#building-mcp-clients) - A tutorial on building clients for the Model Context Protocol, which enhances LLM capabilities.
3. [LangGraph](https://langchain-ai.github.io/langgraph/) - A framework for building agentic systems with LLMs, simplifying the implementation of workflows.
4. [Amazon Bedrock's AI Agent Framework](https://aws.amazon.com/bedrock/agents/) - Information on Amazon's framework for building AI agents, useful for developers looking to implement agentic systems.
5. [Rivet](https://rivet.ironcladapp.com/) - A drag-and-drop GUI tool for building and testing complex workflows with LLMs.
## Topics

![](topics/Concept/Agentic%20Systems)