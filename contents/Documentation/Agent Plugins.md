---
already_read: true
link: https://agent-plugins.org/
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- AI_agent
type: Content
upload_date: '2026-08-25'
---

https://agent-plugins.org/

## Summary

Agent Plugins is an open standard for portable, reusable AI agent components that work across different clients.

**Core concept**
- Open, vendor-neutral standard for packaging AI agent plugins (v1.0.0).
- Enables consistent discovery and loading of Agent Skills and MCP servers across compatible clients.

**Problem solved**
- Eliminates need to duplicate/repackage components for each client’s proprietary plugin format.

**Package structure**
- Directory with required `plugin.json` manifest and optional components in fixed paths.
- `skills/` for Agent Skills, `mcp.json` for MCP servers, client-specific extensions in reverse-domain namespaces.

**Governance**
- Openly licensed, developed in public with Technical Steering Committee (Amazon, Cursor, Microsoft, OpenAI, Vercel).
- Public proposals, GitHub Discussions for async collaboration, Discord for sync discussions.

**Resources**
- Specification, JSON schemas, governance, and contribution docs available in public repository.

## Links

- [Agent Plugins Specification Repository](https://github.com/agentplugins/agent-plugins-spec) : The official GitHub repository for the Agent Plugins specification, including proposals, technical decisions, and governance details. This is the core repository for understanding the standard and contributing to its development.
- [Agent Skills Specification](https://agentskills.io/specification) : The specification for Agent Skills, a key component of Agent Plugins that defines the format and structure for portable skills within plugins.
- [Model Context Protocol (MCP) Specification](https://modelcontextprotocol.io/specification) : The specification for the Model Context Protocol (MCP), which is referenced in Agent Plugins for describing MCP servers (e.g., stdio, Streamable HTTP, or legacy HTTP+SSE) within plugins.


## Topics

![[topics/Platform/Agent Plugins]]

![[topics/Tool/MCP servers]]

![[topics/Concept/Agent Skills]]