---
already_read: true
link: https://platform.claude.com/docs/en/managed-agents/overview
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- AI_agent
type: Content
upload_date: '2026-05-23'
---

https://platform.claude.com/docs/en/managed-agents/overview
## Summary

Claude Managed Agents is a pre-built, configurable agent harness for running Claude as an autonomous agent in managed infrastructure, ideal for long-running and asynchronous tasks. Key technical points include:

- **Core Concepts**: Agent (model, tools, skills), Environment (cloud container/self-hosted sandbox), Session (running agent instance), Events (message exchanges).
- **Workflow**: Define agent/environment → Start session → Stream events/responses → Steer or interrupt mid-execution.
- **Use Cases**: Long-running tasks, cloud/self-hosted execution, minimal infrastructure needs, stateful sessions.
- **Tools**: Built-in support for Bash, file operations, web search/fetch, and MCP servers.
- **Beta Features**: Requires `managed-agents-2026-04-01` header; some features (e.g., MCP tunnels) are in research preview.
- **Stateful Design**: Sessions persist conversation history/server-side data (no Zero Data Retention/HIPAA BAA eligibility).
- **Rate Limits**: 300/min (create ops), 600/min (read ops); organization-level spend limits apply.
- **Branding**: Partners must avoid Anthropic product name confusion (e.g., "Claude Agent" is preferred).
## Links

- [Claude Managed Agents Documentation](https://claude.com/partners/mcp) : Documentation for Claude Managed Agents, covering agent setup, tools, and configurations.
- [Claude Platform on AWS](https://claude.com/partners/amazon-bedrock) : Details about deploying Claude Managed Agents on Amazon Bedrock (AWS), including cloud infrastructure and feature availability.
- [Claude Managed Agents Quickstart Guide](https://claude.com/form/claude-managed-agents) : A quickstart guide for creating and configuring Claude Managed Agents, aligned with the 'Quickstart' section in the content.
- [Claude Managed Agents API Reference](https://claude.com/resources/use-cases) : API reference documentation for Claude Managed Agents, including endpoints, tools, and integration details.
- [Claude Managed Agents Use Cases and Resources](https://claude.com/solutions/agents) : Resources and use cases for Claude Managed Agents, providing insights into practical applications and workloads.

## Topics

![[topics/Tool/Claude Managed Agents]]

![[topics/Platform/Claude Platform on AWS]]

![[topics/Concept/Agent Loop]]

![[topics/Concept/Model Context Protocol MCP Servers]]

![[topics/Concept/AI Sandboxing]]

![[topics/Concept/Server Sent Events SSE]]

![[topics/Concept/State Management in AI Agents]]

![[topics/Concept/API Rate Limiting]]

![[topics/Concept/Prompt Caching]]