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

The article introduces smolagents, a simple library for building agents that write actions in code. Key points include:

- **Agents**: Programs where LLM outputs control the workflow, with agency varying on a continuous spectrum.
- **When to Use Agents**: Useful for tasks requiring flexibility in workflow, but often overkill for simple, predetermined tasks.
- **Code Agents**: Agents that write actions in code are more effective than JSON-like formats due to better composability, object management, generality, and representation in LLM training data.
- **smolagents Library**: Features simplicity, first-class support for code agents, hub integrations, and support for any LLM.
- **Building an Agent**: Requires tools (functions with type hints and docstrings) and a model (any LLM).
- **Benchmarking**: Open-source models with smolagents can compete with closed models.
- **Next Steps**: Guided tours, tutorials, examples, and further reading on agents.

The article also includes community comments and discussions on the library.
## Links

- [Guided Tour of Smolagents](https://huggingface.co/docs/smolagents/guided_tour) : A guided tour of the smolagents library, helping users familiarize themselves with the basics and core functionalities.
- [Building Good Agents Tutorial](https://huggingface.co/docs/smolagents/tutorials/building_good_agents) : A tutorial on building effective agents using the smolagents library, covering best practices and detailed examples.
- [Smolagents GitHub Repository](https://github.com/huggingface/smolagents) : The official GitHub repository for smolagents, containing the source code, examples, and additional resources for developers.
- [Anthropic's Guide to Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) : An in-depth guide by Anthropic on building effective agents, providing insights and methodologies for creating robust agentic systems.

## Topics

![[topics/Tool/DuckDuckGoSearchTool]]

![[topics/Tool/HfApiModel]]

![[topics/Library/smolagents]]