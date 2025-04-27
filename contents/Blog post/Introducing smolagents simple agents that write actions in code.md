---
already_read: false
link: https://huggingface.co/blog/smolagents
read_priority: 2
relevance: 0
source: Data Elixir
tags:
- AI_agent
type: Content
upload_date: '2025-01-08'
---

https://huggingface.co/blog/smolagents
## Summary

smolagents is a library designed for building simple AI agents that can execute actions in code, enhancing the capabilities of language models (LLMs). Key insights include:

- **Definition of Agents**: Agents allow LLMs to have agency by controlling workflows using real-world tools and information. The level of agency is continuous, ranging from no impact on program flow to controlling iterative workflows and potentially multi-agent systems.

- **Use Cases**: Agents are beneficial for flexible workflows that cannot be predetermined, though they may be overkill for simpler tasks. Examples illustrate when to stick with a deterministic approach versus adopting agents for complex scenarios.

- **Code Agents**: A proposed structure where agents can write their actions as code is more effective than using JSON-like snippets, enhancing composability, object management, and generality.

- **Features of smolagents**: 
   - Built for simplicity with minimal abstractions.
   - Supports Code Agents and traditional ToolCallingAgents.
   - Integrates easily with various LLMs and tools.
   - Is positioned as a successor to transformers.agents.

- **Building an Agent**: Requires defining tools and selecting an LLM. Example code demonstrates how to create a travel duration tool and utilize it in a travel planner agent.

- **Performance**: Open models in agentic workflows can now compete with closed models, with evidence from benchmarks suggesting improved capabilities.

- **Next Steps**: Users are encouraged to explore guided tours, tutorials, and examples to implement agentic solutions effectively.

Overall, smolagents provides a streamlined way to harness LLMs for executing complex workflows while maintaining user-friendly access and integration capabilities.
## Links

- [Building Good Agents Tutorial](https://huggingface.co/docs/smolagents/tutorials/building_good_agents) : An in-depth guide on how to construct robust agents using the smolagents library.
- [Examples of RAG with smolagents](https://huggingface.co/docs/smolagents/examples/rag) : Example implementation of retrieval-augmented generation (RAG) using smolagents.
- [Tool Reference for smolagents](https://huggingface.co/docs/smolagents/reference/tools#smolagents.Tool) : Reference documentation for the Tool feature within the smolagents framework.
- [CodeAgent Reference](https://huggingface.co/docs/smolagents/reference/agents#smolagents.CodeAgent) : Detailed explanation and usage of the CodeAgent class in smolagents.
- [Benchmark Notebook for Smolagents](https://github.com/huggingface/smolagents/blob/main/examples/benchmark.ipynb) : A Jupyter notebook that compares different models and setups with smolagents.

## Topics

![](topics/Library/smolagents)

![](topics/Concept/Agentic%20Workflows)

![](topics/Tool/CodeAgent)

![](topics/Concept/Multi%20Agent%20Systems)

![](topics/Tool/HfApiModel)

![](topics/Concept/Tool%20Calling%20in%20AI%20Agents)