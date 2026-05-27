---
already_read: true
link: https://webmcp.dev/
read_priority: 0
relevance: 4
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-05-27'
---

https://webmcp.dev/
## Summary

WebMCP is an open-source JavaScript library enabling websites to integrate with the Model Context Protocol (MCP), featuring a blue widget for LLM/agent interaction. Key technical points:

**For Users:**
- Requires an MCP client (e.g., Claude Desktop) configured with a WebMCP server.
- Users generate a token via the MCP client and paste it into the widget to enable interaction.

**For Developers:**
- Simple integration: include `webmcp.js` to auto-initialize the widget.
- **Core Features:**
  - **Tools:** Register functions (e.g., `weather`) for LLMs to perform actions. Tools must be registered post-script load for client compatibility.
  - **Prompts:** Predefined templates (e.g., Git commit messages) with dynamic arguments.
  - **Resources:** Expose data (e.g., page content, DOM elements) via URIs for LLM context.
  - **Sampling:** Secure LLM request handling via user-approved dialogs (e.g., SQL generation queries).

**Example Workflow:**
- Developer registers tools/prompts/resources via `registerTool`, `registerPrompt`, or `registerResource`.
- User interacts via the widget, enabling agentic behaviors while maintaining privacy.
## Links

- [WebMCP GitHub Repository](https://github.com/jasonjmcghee/WebMCP) : This is the official GitHub repository for WebMCP, an open-source JavaScript library that enables websites to integrate with the Model Context Protocol (MCP). It provides details about the library, its installation, usage, and contribution guidelines.
- [Claude Desktop Download Page](https://claude.ai/download) : This link directs to the download page for Claude Desktop, an MCP client that can be used to interact with WebMCP-enabled websites. It includes instructions for configuring the client to work with WebMCP. This is essential for users looking to test or use WebMCP features.

## Topics

![[topics/Library/WebMCP]]

![[topics/Concept/Sampling in MCP]]

![[topics/Concept/Model Context Protocol MCP]]

![[topics/Concept/MCP Client]]

![[topics/Concept/MCP Server]]