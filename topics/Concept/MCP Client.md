---
type: Concept
---

An application or system that interacts with an MCP (Model Control Protocol) server to leverage tools, resources, and prompts exposed by the server. MCP Clients, such as Claude Desktop, Cursor, or Cline, enable LLMs to dynamically call external functions or access data, expanding their functionality beyond native capabilities. Clients typically connect to MCP servers via standardized protocols like HTTP or STDIO and require configuration to specify the server's URL or command-line arguments. MCP Clients can connect to multiple servers through a unified interface and may use client libraries, such as those provided by FastMCP, to support various transports and handle advanced patterns like server-initiated LLM sampling requests.