---
already_read: false
link: https://huggingface.co/blog/smolagents
read_priority: 2
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
- Generative_AI
type: Content
upload_date: '2025-01-08'
---

https://huggingface.co/blog/smolagents
## Summary

smolagents is a new library designed to simplify the creation of AI agents that can perform actions in code. It allows language models (LLMs) to interact with external tools and execute workflows based on their outputs. Key points include:

- **Definition of Agents**: Agents are systems where LLM outputs control workflows, allowing for varying levels of agency based on how much influence the LLM has on the program's flow.

- **When to Use Agents**: Agents are beneficial for complex tasks where predefined workflows are insufficient. However, they may be unnecessary for simpler tasks where deterministic workflows suffice.

- **Code Agents**: The library emphasizes writing actions in code rather than JSON, enhancing composability, object management, and generality.

- **Building an Agent**: To create an agent, users need to define tools (functions) and select an LLM. The library supports various models, including those from Hugging Face and other providers.

- **Performance of Open Models**: Benchmarks indicate that open-source models can perform comparably to closed models in agentic workflows.

Next steps include exploring guided tours, tutorials, and examples to effectively utilize the library.
## Links

1. [Hugging Face Smolagents Tutorial on Tools](https://huggingface.co/docs/smolagents/tutorials/tools) - A comprehensive guide on how to create and use tools within the smolagents library.
2. [Building Effective Agents by Anthropic](https://www.anthropic.com/research/building-effective-agents) - A research paper discussing the principles and practices for developing effective AI agents.
3. [Hugging Face Smolagents Examples: RAG](https://huggingface.co/docs/smolagents/examples/rag) - Examples demonstrating how to implement retrieval-augmented generation (RAG) with smolagents.
4. [Hugging Face Smolagents Examples: Text to SQL](https://huggingface.co/docs/smolagents/examples/text_to_sql) - A tutorial on converting natural language queries into SQL using smolagents.
5. [Hugging Face Smolagents Guided Tour](https://huggingface.co/docs/smolagents/guided_tour) - An introductory tour to familiarize users with the smolagents library and its capabilities.
## Topics

![](topics/Library/SmolAgents)

![](topics/Concept/Agentic%20Systems)

![](topics/Tool/CodeAgent)

![](topics/Tool/DuckDuckGoSearchTool)

![](topics/Model/HfApiModel)