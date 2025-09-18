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

Anthropic's guide on building effective AI agents emphasizes simplicity and composability over complex frameworks. They define agents as systems where LLMs dynamically direct their own processes, distinguishing them from workflows that follow predefined paths. The guide recommends starting with simple solutions and only increasing complexity when necessary, as agentic systems often trade latency and cost for better task performance.

Key patterns for agentic systems include:

1. **Augmented LLM**: The basic building block, enhanced with capabilities like retrieval, tools, and memory.
2. **Prompt Chaining**: Decomposing tasks into sequences of steps, with programmatic checks on intermediate steps.
3. **Routing**: Classifying inputs and directing them to specialized tasks.
4. **Parallelization**: Running tasks simultaneously and aggregating outputs, with variations like sectioning and voting.
5. **Orchestrator-Workers**: A central LLM dynamically breaks down tasks, delegates them to worker LLMs, and synthesizes results.
6. **Evaluator-Optimizer**: One LLM generates responses while another provides evaluation and feedback in a loop.

Agents are suitable for open-ended problems where the number of steps is unpredictable, and they operate autonomously with human oversight. The guide advises thorough testing and clear tool documentation for agent implementations.

The guide also discusses the use of frameworks, suggesting that developers start with LLM APIs directly and understand the underlying code before using frameworks. It concludes with principles for successful agent implementation: maintaining simplicity, prioritizing transparency, and carefully crafting the agent-computer interface.

Appendices provide practical examples of agents in customer support and coding, and offer tips on prompt engineering for tools.
## Links

- [LangGraph from LangChain](https://langchain-ai.github.io/langgraph/) : LangGraph from LangChain is a framework for building agentic systems, simplifying standard low-level tasks like calling LLMs, defining and parsing tools, and chaining calls together.
- [Amazon Bedrock's AI Agent framework](https://aws.amazon.com/bedrock/agents/) : Amazon Bedrock's AI Agent framework is a tool that makes it easy to get started by simplifying standard low-level tasks like calling LLMs, defining and parsing tools, and chaining calls together.
- [Vellum](https://www.vellum.ai/) : Vellum is a GUI tool for building and testing complex workflows, making it easier to implement agentic systems.
- [Rivet](https://rivet.ironcladapp.com/) : Rivet is a drag and drop GUI LLM workflow builder, simplifying the implementation of agentic systems.
- [Model Context Protocol](https://modelcontextprotocol.io/tutorials/building-a-client#building-mcp-clients) : The Model Context Protocol allows developers to integrate with a growing ecosystem of third-party tools with a simple client implementation, enhancing the capabilities of LLMs.

## Topics

![[topics/Concept/AI Agents)]]

![[topics/Concept/Routing)]]

![[topics/Concept/Orchestrator Workers)]]

![[topics/Concept/Evaluator Optimizer)]]

![[topics/Concept/Parallelization)]]

![[topics/Concept/Prompt Chaining)]]

![[topics/Concept/Agentic Systems)]]

![[topics/Concept/Augmented LLM)]]