---
already_read: true
link: https://learn.microsoft.com/en-us/agent-framework/overview/
read_priority: 0
relevance: 5
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-05-06'
---

https://learn.microsoft.com/en-us/agent-framework/overview/
## Summary

Microsoft Agent Framework provides two core capabilities: **agents** (individual LLM-based agents for tasks like tool use and multi-turn conversations) and **workflows** (graph-based orchestration for multi-step processes with type safety and human-in-the-loop support). It includes foundational components like model clients, session management, context providers, middleware, and MCP clients for tool integration.

Key features:
- Supports multiple LLM providers (Microsoft Foundry, Anthropic, Azure OpenAI, etc.).
- Enables stateful, interactive AI applications with enterprise-grade features (telemetry, safety filters).
- Combines simplicity (AutoGen) with enterprise features (Semantic Kernel).

Use cases:
- **Agents**: Open-ended tasks, autonomous tool use.
- **Workflows**: Well-defined multi-step processes with explicit control.

Quick start examples provided for .NET and Python. Migration guides available from AutoGen/Semantic Kernel. Note: Third-party integrations are at the user's risk; responsible AI practices are required.
## Links

- [AutoGen GitHub Repository](https://github.com/microsoft/autogen) : Official GitHub repository for AutoGen, a framework for building AI agents. Mentioned as a predecessor to the Microsoft Agent Framework.
- [Semantic Kernel GitHub Repository](https://github.com/microsoft/semantic-kernel) : Official GitHub repository for Semantic Kernel, an enterprise-grade framework for AI agents and workflows. Mentioned as a predecessor to the Microsoft Agent Framework.
- [Semantic Kernel Documentation for Agent Framework](https://github.com/MicrosoftDocs/semantic-kernel-docs/blob/main/agent-framework/overview/index.md) : Documentation for the Agent Framework within the Semantic Kernel repository, providing additional context and details.
- [Agent Framework Transparency FAQ](https://github.com/microsoft/agent-framework/blob/main/TRANSPARENCY_FAQs.md) : FAQ document for the Agent Framework, focusing on transparency and responsible AI usage.

## Topics

![[topics/Library/Microsoft Agents AI Foundry]]

![[topics/Concept/Graph based Workflows]]

![[topics/Concept/State Management]]

![[topics/Concept/Middleware in AI Agents]]

![[topics/Concept/Telemetry in AI Systems]]

![[topics/Concept/Type Safety]]

![[topics/Concept/Migration Guide for AI Frameworks]]

![[topics/Concept/AI Agents]]

![[topics/Concept/Model Context Protocol MCP]]

![[topics/Concept/Human in the Loop]]