---
already_read: false
link: https://huggingface.co/blog/smolagents
read_priority: 2
relevance: 0
source: Data Elixir
tags:
- AI_agent
- Development_tool
type: Content
upload_date: '2025-01-08'
---

https://huggingface.co/blog/smolagents
## Summary

Hugging Face introduces smolagents, a simple library for building agents that write actions in code. Agents are programs where LLM outputs control the workflow, with agency levels ranging from simple processors to multi-agent systems. Agents are useful when flexibility is needed in workflows, but they can be overkill for simple, deterministic tasks. Smolagents supports code agents, which write actions in code rather than JSON, offering better composability, object management, generality, and representation in LLM training data. The library is designed for simplicity, first-class support for code agents, hub integrations, and compatibility with any LLM. To build an agent, you need tools and a model, with tools being simple functions decorated with @tool. Smolagents also supports sharing tools to the Hub. A comparison of open-source models with closed models shows that open-source models can now compete with the best closed models in agentic workflows. Next steps include studying tutorials, diving into examples, and reading more on agents.
## Links

- [smolagents GitHub Repository](https://github.com/huggingface/smolagents) : The GitHub repository for smolagents, a simple library to build agents.
- [Guided Tour of smolagents](https://huggingface.co/docs/smolagents/guided_tour) : A guided tour to familiarize yourself with the smolagents library.
- [Tools Tutorial](https://huggingface.co/docs/smolagents/tutorials/tools) : In-depth tutorials to learn more about tools and general best practices in smolagents.
- [Building Good Agents Tutorial](https://huggingface.co/docs/smolagents/tutorials/building_good_agents) : Tutorial on building good agents with smolagents.
- [Anthropic Blog on Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) : An excellent blog post by Anthropic providing solid general knowledge on building effective agents.

## Topics

![](topics/Library/smolagents)

![](topics/Concept/AI%20Agents)

![](topics/Concept/Code%20Agents)

![](topics/Concept/Multi%20step%20Agent)

![](topics/Concept/ToolCallingAgent)