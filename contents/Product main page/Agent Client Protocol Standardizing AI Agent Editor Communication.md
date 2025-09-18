---
already_read: true
link: https://agentclientprotocol.com/overview/introduction
read_priority: 0
relevance: 5
source: null
tags:
- AI_agent
- Development_tool
type: Content
upload_date: '2025-09-17'
---

https://agentclientprotocol.com/overview/introduction
## Summary

The Agent Client Protocol (ACP) is a developing standard that aims to streamline communication between code editors (IDEs, text editors, etc.) and coding agents (AI-powered programs that autonomously modify code). The protocol addresses several issues in the current landscape, including integration overhead, limited compatibility, and developer lock-in, by providing a standardized protocol for agent-editor communication, similar to the Language Server Protocol (LSP).

ACP assumes that the user primarily operates within their editor and uses agents for specific tasks. Agents run as sub-processes of the code editor and communicate using JSON-RPC over stdio. The protocol reuses JSON representations from the Machine Communication Protocol (MCP) where possible and includes custom types for agentic coding user experience elements, such as displaying diffs. The default format for user-readable text is Markdown, allowing rich formatting without requiring HTML rendering capabilities in the code editor.
## Links

- [Agent Client Protocol GitHub Repository](https://github.com/zed-industries/agent-client-protocol) : The GitHub repository for the Agent Client Protocol, where you can find the source code and contribute to the project.
- [Language Server Protocol](https://microsoft.github.io/language-server-protocol/) : The Language Server Protocol (LSP) documentation, which standardizes language server integration, similar to what ACP aims to do for agent-editor communication.

## Topics

![[topics/Concept/Agent Client Protocol)]]