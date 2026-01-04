---
already_read: true
link: https://blog.modelcontextprotocol.io/posts/2025-11-25-first-mcp-anniversary/
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2026-01-04'
---

https://blog.modelcontextprotocol.io/posts/2025-11-25-first-mcp-anniversary/
## Summary

The Model Context Protocol (MCP) celebrates its one-year anniversary with the release of the November 2025 specification. Over the past year, MCP has grown from an open-source experiment to the de-facto standard for connecting data and applications to Large Language Models (LLMs). The ecosystem has flourished, with thousands of active MCP servers and a vibrant community contributing to its development.

Key updates in the November 2025 release include:

- **Task-based Workflows**: Introduces a new abstraction for tracking work performed by MCP servers, supporting states like working, input_required, completed, failed, and cancelled. This feature is experimental and aims to address complex, multi-step operations.

- **Simplified Authorization Flows**: Addresses pain points with Dynamic Client Registration (DCR) by introducing URL-based client registration using OAuth Client ID Metadata Documents. This simplifies the process for MCP server developers.

- **Security and Enterprise Features**: Enhancements include client security requirements for local server installation and default scopes definition in the authorization specification. The vision for internal registries with self-managed governance controls and security coverage is also established.

- **Extensions**: Introduces the concept of extensions to the protocol, allowing for scenario-specific additions that follow MCP conventions without requiring full protocol integration. This includes authorization extensions like OAuth client credentials support and enterprise IdP policy controls.

- **URL Mode Elicitation**: Enables secure out-of-band interactions by allowing users to authenticate securely in their browser without the client seeing the entered credentials.

- **Sampling with Tools**: Allows MCP servers to run their own agentic loops using the client’s tokens, reducing the complexity of client implementations and enabling tool calling in sampling requests.

- **Developer Experience Improvements**: Includes standardized formats for tool names, decoupled request payloads from RPC methods, SSE polling via server-side disconnect, and improved specification version management for SDKs.

The community's role in MCP's success is highlighted, with contributions from developers, organizations, and maintainers. The protocol's governance structure, which involves community leaders and maintainers, has proven valuable in moving faster on critical improvements.

Looking ahead, MCP aims to enable new categories of AI-powered applications, with a focus on reliability, observability, server composition, and security. The community's creativity and real-world feedback will continue to shape the protocol's evolution.

To get started with the latest MCP specification release, resources include the changelog, documentation, and engagement through GitHub and Discord.
## Links

- [Model Context Protocol Documentation](https://modelcontextprotocol.io/docs) : The official documentation for the Model Context Protocol, providing detailed information on the protocol's specifications, tutorials, and guides.
- [GitHub Repository for Model Context Protocol](https://github.com/modelcontextprotocol/modelcontextprotocol) : The GitHub repository for the Model Context Protocol, where you can find the source code, issues, and contributions related to the protocol.
- [Hugging Face MCP Server](https://huggingface.co/) : Hugging Face's MCP server for model management and dataset search, making it easier to integrate models and datasets with the Model Context Protocol.

## Topics

![[topics/Concept/Task based Workflows]]

![[topics/Concept/Authorization Extensions]]

![[topics/Concept/URL Mode Elicitation]]

![[topics/Concept/Sampling with Tools]]

![[topics/Concept/MCP Registry]]

![[topics/Concept/Model Context Protocol MCP]]