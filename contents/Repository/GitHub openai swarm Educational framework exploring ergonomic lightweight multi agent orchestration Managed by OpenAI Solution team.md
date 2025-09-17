---
already_read: true
link: https://github.com/openai/swarm/tree/main
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- AI_agent
- Development_tool
type: Content
upload_date: '2024-10-15'
---

https://github.com/openai/swarm/tree/main
## Summary

Swarm is an educational framework for lightweight, multi-agent orchestration, managed by OpenAI. It is now replaced by the OpenAI Agents SDK, which is recommended for production use. Swarm focuses on making agent coordination and execution lightweight, highly controllable, and easily testable through two primitive abstractions: Agents and handoffs. Agents can hand off conversations to other Agents and are powered by the Chat Completions API, making them stateless between calls.

Key features include:
- **Agents**: Encapsulate instructions and tools, can hand off to other Agents.
- **Functions**: Agents can call Python functions directly, with support for context variables and error handling.
- **Streaming**: Supports streaming responses with additional event types for Agent switches.
- **Examples**: Provides various examples like basic setup, function calling, and multi-agent setups.

Swarm is designed for developers curious about multi-agent orchestration and is not related to the Assistants API. It is suitable for scenarios with a large number of independent capabilities and instructions that are difficult to encode into a single prompt. The framework encourages developers to bring their own evaluation suites to test performance.
## Links

- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) : The production-ready evolution of Swarm, featuring key improvements and actively maintained by the OpenAI team.
- [Chat Completions API](https://platform.openai.com/docs/api-reference/chat/create#chat-create-messages) : The API documentation for chat completions, which Swarm is entirely powered by and is stateless between calls.

## Topics

![](topics/Concept/Multi%20agent%20orchestration)

![](topics/Concept/Agent%20Handoffs)

![](topics/Concept/Swarm%20Framework)