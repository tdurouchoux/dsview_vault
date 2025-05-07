---
already_read: true
link: https://github.com/getzep/graphiti
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Graph
- AI_agent
- Data_Engineering
type: Content
upload_date: '2025-05-07'
---

https://github.com/getzep/graphiti
## Summary

Graphiti is an open-source framework designed for constructing real-time, temporally-aware knowledge graphs specifically for AI agents. It integrates dynamic user interactions and enterprise data to create a cohesive, queryable graph, providing a notable advantage over traditional retrieval-augmented generation (RAG) methods by facilitating real-time updates, efficient retrieval, and precise historical queries.

Key features include:
- **Real-Time Incremental Updates:** Enables immediate data integration without the need for batch processing.
- **Bi-Temporal Data Model:** Tracks both event occurrence and data ingestion times for accurate temporal queries.
- **Hybrid Retrieval Methods:** Allows low-latency queries using semantic, keyword, and graph-based approaches.
- **Custom Entity Definitions:** Supports flexible ontology creation through Pydantic models, suitable for enterprise-scale data.

Graphiti contrasts significantly with existing solutions like GraphRAG by offering continuous data management, higher adaptability, and explicit temporal handling, making it a robust option for applications requiring real-time interaction.

Installation requires Python 3.10+, Neo4j, and an API key from a compatible LLM service, with examples provided for initial setup and integrating with Azure OpenAI and Google Gemini. The framework continues to evolve, with a roadmap that includes enhancing retrieval capabilities and supporting custom graph schemas, making it a promising tool for developing advanced AI applications.
## Links

- [Graphiti Quick Start Guide](https://help.getzep.com/graphiti/graphiti/quick-start) : A comprehensive guide to getting started with Graphiti, including installation and usage examples.
- [State of the Art in Agent Memory](https://blog.getzep.com/state-of-the-art-agent-memory/) : An article discussing the advancements in agent memory using Graphiti.
- [Neo4j Download Page](https://neo4j.com/download/) : Official page to download Neo4j, which serves as the backend for Graphiti's embeddings storage.
- [Graphiti GitHub Repository](https://github.com/getzep/graphiti/releases) : Access the GitHub repository for Graphiti to find releases and detailed project information.
- [Building Agents with LangChain and Graphiti](https://help.getzep.com/graphiti/graphiti/lang-graph-agent) : Explore how to integrate Graphiti with LangChain to build enhanced AI agents.

## Topics

![](topics/Library/Graphiti)

![](topics/Concept/Knowledge%20Graph)

![](topics/Platform/Neo4j)

![](topics/Concept/Incremental%20Data%20Updates)

![](topics/Concept/Hybrid%20Retrieval%20Methods)