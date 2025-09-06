---
already_read: false
link: https://www.anthropic.com/engineering/building-effective-agents
read_priority: 4
relevance: 0
source: Blef
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2025-03-09'
---

https://www.anthropic.com/engineering/building-effective-agents
## Summary

Anthropic's guide on building effective AI agents emphasizes simplicity and composability over complex frameworks. Key points include:

- **Agent Definitions**: Agents are categorized into workflows (predefined code paths) and dynamic agents (LLMs directing their own processes).
- **When to Use Agents**: Agents are suitable for complex, open-ended tasks requiring flexibility and model-driven decision-making, while simpler tasks may only need optimized single LLM calls.
- **Frameworks**: Frameworks like LangGraph and Amazon Bedrock's AI Agent framework can simplify implementation but may add unnecessary complexity. Direct use of LLM APIs is often more straightforward.
- **Building Blocks**: The augmented LLM is the foundational building block, enhanced with capabilities like retrieval, tools, and memory. Key patterns include:
  - **Prompt Chaining**: Decomposing tasks into sequences of steps.
  - **Routing**: Classifying inputs and directing them to specialized tasks.
  - **Parallelization**: Running tasks simultaneously for speed or diverse outputs.
  - **Orchestrator-Workers**: Dynamically breaking down tasks and delegating them to worker LLMs.
  - **Evaluator-Optimizer**: Iterative refinement of responses with evaluation and feedback.
- **Agents**: Autonomous systems that plan and operate independently, using tools and environmental feedback. They are suitable for open-ended problems where the number of steps is unpredictable.
- **Best Practices**: Maintain simplicity, prioritize transparency, and carefully craft the agent-computer interface. Frameworks can help initially, but reducing abstraction layers in production is often beneficial.
- **Applications**: Agents are particularly valuable in customer support and coding, where they can handle complex tasks with clear success criteria and enable feedback loops.
- **Tool Engineering**: Effective tool definitions and specifications are crucial. Tools should be easy for the LLM to use, with clear descriptions, example usage, and edge cases. Testing and iterating on tool usage is essential for optimal performance.

The guide concludes by emphasizing the importance of starting simple and only increasing complexity when necessary, ensuring that agents are reliable, maintainable, and trusted by their users.
## Links

- [Vellum](https://www.vellum.ai/) : Vellum is a GUI tool for building and testing complex workflows.
- [LangGraph](https://langchain-ai.github.io/langgraph/) : LangGraph from LangChain is a framework that makes agentic systems easier to implement.
- [Amazon Bedrock's AI Agent framework](https://aws.amazon.com/bedrock/agents/) : Amazon Bedrock's AI Agent framework is a framework that makes agentic systems easier to implement.
- [Rivet](https://rivet.ironcladapp.com/) : Rivet is a drag and drop GUI LLM workflow builder.
- [Model Context Protocol](https://modelcontextprotocol.io/tutorials/building-a-client#building-mcp-clients) : Model Context Protocol allows developers to integrate with a growing ecosystem of third-party tools with a simple client implementation.

## Topics

![](topics/Concept/Agentic%20Systems)

![](topics/Concept/Augmented%20LLM)

![](topics/Concept/Prompt%20Chaining)

![](topics/Concept/Routing)

![](topics/Concept/Parallelization)

![](topics/Concept/Orchestrator%20Workers)

![](topics/Concept/Evaluator%20Optimizer)

![](topics/Concept/Autonomous%20Agents)

![](topics/Concept/Model%20Context%20Protocol)