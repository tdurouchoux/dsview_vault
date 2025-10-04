---
already_read: false
link: https://developer.chrome.com/blog/chrome-devtools-mcp
read_priority: 5
relevance: 0
source: Alpha Signal
tags:
- AI_agent
type: Content
upload_date: '2025-10-04'
---

https://developer.chrome.com/blog/chrome-devtools-mcp
## Summary

The Chrome DevTools Model Context Protocol (MCP) server is introduced to enhance AI coding assistants by enabling them to debug web pages directly in Chrome. This protocol addresses the limitation of AI agents not being able to see the real-time effects of the code they generate.

Key points:

- **Model Context Protocol (MCP)**: An open-source standard for connecting large language models (LLMs) to external tools and data sources. The Chrome DevTools MCP server adds debugging capabilities to AI agents.
- **Capabilities**: AI agents can use tools like `performance_start_trace` to start Chrome, open websites, and record performance traces for analysis. This helps in identifying and fixing issues more accurately.
- **Use Cases**: The MCP server can be used for real-time code verification, diagnosing network and console errors, simulating user behavior, debugging live styling and layout issues, and automating performance audits.
- **Getting Started**: To use the Chrome DevTools MCP server, add a config entry to your MCP client and run prompts to check performance metrics or diagnose issues.
- **Community Involvement**: The project is in its public preview phase, and feedback from developers and vendors is encouraged to shape future capabilities.

For more details, refer to the Chrome DevTools MCP documentation on GitHub.
## Links

- [Model Context Protocol (MCP) documentation](https://modelcontextprotocol.io/docs/getting-started/intro) : Documentation for the Model Context Protocol (MCP), an open-source standard for connecting large language models (LLMs) to external tools and data sources.
- [Chrome DevTools MCP documentation](https://github.com/ChromeDevTools/chrome-devtools-mcp/blob/main/docs/tool-reference.md) : Tool reference documentation for the Chrome DevTools MCP server, providing a list of all available tools and their usage.

## Topics

![[topics/Tool/Chrome DevTools Model Context Protocol MCP server]]

![[topics/Concept/Model Context Protocol MCP]]