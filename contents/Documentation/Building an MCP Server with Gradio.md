---
already_read: false
link: https://www.gradio.app/guides/building-mcp-server-with-gradio
read_priority: 3
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2026-03-23'
---

https://www.gradio.app/guides/building-mcp-server-with-gradio
## Summary

To build an MCP server with Gradio, set `mcp_server=True` in `.launch()`. Install Gradio with `pip install "gradio[mcp]"` and ensure you have an MCP-compatible LLM client (e.g., Claude Desktop). The server converts Gradio functions into MCP tools, using docstrings and type hints for tool descriptions. Key features include automatic file handling, environment variable support (`GRADIO_MCP_SERVER=True`), and hosted MCP servers on Hugging Face Spaces. For authentication, use `gr.Request` or `gr.Header` to access request metadata. Progress updates can be sent via `gr.Progress`. Tools, resources, and prompts can be customized using decorators (`@gr.mcp.tool`, `@gr.mcp.resource`, `@gr.mcp.prompt`). For MCP-only functions, use `gr.api`. For advanced setups, integrate with FastMCP for state management and user identification. Troubleshoot by ensuring valid docstrings, type hints, and MCP client compatibility. Use the MCP Inspector Tool for debugging.
## Links

- [Gradio API Documentation](https://www.gradio.app/main/docs/gradio/api) : Official Gradio API documentation, covering MCP integration and API endpoint management.
- [Gradio Request Class Documentation](https://www.gradio.app/main/docs/gradio/request) : Documentation for the gr.Request class, essential for accessing request metadata in MCP server development.
- [Model Context Protocol (MCP) Python SDK](https://github.com/modelcontextprotocol/python-sdk) : Official GitHub repository for the MCP Python SDK, providing tools for building and interacting with MCP servers.
- [MCP Inspector Tool](https://github.com/modelcontextprotocol/inspector) : A debugging tool for MCP servers, useful for troubleshooting and testing Gradio-based MCP servers.
- [Hugging Face Spaces](https://huggingface.co/spaces) : Platform for hosting and sharing Gradio apps as MCP servers, enabling scalable cloud deployments.

## Topics

![[topics/Concept/Model Context Protocol MCP]]

![[topics/Platform/Hugging Face]]

![[topics/Concept/Model Context Protocol MCP Resources and Servers]]

![[topics/Concept/MCP Prompts]]

![[topics/Concept/MCP Client]]

![[topics/Library/Gradio]]

![[topics/Tool/FastMCP]]

![[topics/Concept/MCP Tools]]