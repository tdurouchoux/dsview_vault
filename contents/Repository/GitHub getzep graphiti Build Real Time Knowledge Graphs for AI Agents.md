---
already_read: true
link: https://github.com/getzep/graphiti
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Graph
- AI_agent
type: Content
upload_date: '2025-05-07'
---

https://github.com/getzep/graphiti
## Summary

Graphiti is a framework for building and querying temporally-aware knowledge graphs tailored for AI agents in dynamic environments. It integrates user interactions, structured and unstructured data, and external information into a coherent, queryable graph, supporting incremental updates, efficient retrieval, and precise historical queries without full graph recomputation.

Key features include real-time incremental updates, a bi-temporal data model for accurate point-in-time queries, hybrid retrieval combining semantic embeddings, keyword (BM25), and graph traversal, custom entity definitions, and scalability for enterprise environments. Graphiti is designed to address the limitations of traditional RAG approaches, which often rely on batch processing and static data summarization.

The framework is part of Zep's Context Engineering Platform, offering agent memory, Graph RAG for dynamic data, and context retrieval and assembly. Graphiti supports various database backends like Neo4j, FalkorDB, Kuzu, and Amazon Neptune, and integrates with LLM providers such as OpenAI, Azure OpenAI, Google Gemini, and Ollama for local LLM support.

Graphiti's installation and configuration are detailed, with support for different database backends and LLM providers. The framework includes a MCP server for AI assistant interaction and a REST service for API interactions. Telemetry is enabled by default but can be disabled, collecting anonymous usage statistics to improve the framework.

The project is open-source under the Apache-2.0 license, with active development and contributions encouraged. Detailed documentation, guides, and API references are available to support users in implementing and customizing Graphiti for their specific needs.
## Links

- [Zep Documentation](https://help.getzep.com/graphiti) : Official documentation for Graphiti, providing detailed guides and API references for building and querying knowledge graphs.
- [Zep Blog](https://blog.getzep.com/state-of-the-art-agent-memory/) : Blog post discussing the state-of-the-art agent memory capabilities of Zep, which utilizes Graphiti for advanced knowledge graph functionalities.

## Topics

![](topics/Concept/Knowledge%20Graph)

![](topics/Concept/Real%20Time%20Incremental%20Updates)

![](topics/Concept/Bi%20Temporal%20Data%20Model)

![](topics/Concept/Hybrid%20Retrieval)

![](topics/Concept/Context%20Engineering)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Model%20Context%20Protocol%20MCP)