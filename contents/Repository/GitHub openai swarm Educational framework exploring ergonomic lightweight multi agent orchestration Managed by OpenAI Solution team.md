---
already_read: true
link: https://github.com/openai/swarm/tree/main
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- AI_agent
type: Content
upload_date: '2024-10-15'
---

https://github.com/openai/swarm/tree/main
## Summary

Swarm is an educational framework by OpenAI for lightweight, ergonomic multi-agent orchestration. It has been replaced by the OpenAI Agents SDK, which is production-ready and actively maintained. Swarm is designed to be highly customizable and scalable, focusing on agent coordination and execution through two main abstractions: Agents and handoffs.

Agents in Swarm encapsulate instructions and tools, and can hand off conversations to other agents. The framework is stateless, running almost entirely on the client, and does not store state between calls. It is powered by the Chat Completions API.

Key features include:
- **Agents**: Represent workflows or steps defined by instructions and functions.
- **Handoffs**: Allow agents to transfer execution to other agents.
- **Functions**: Agents can call Python functions directly, which can return strings, other agents, or update context variables.
- **Streaming**: Supports streaming responses, similar to the Chat Completions API, with additional event types for agent switches.
- **Evaluations**: Encourages developers to bring their own evaluation suites to test performance.

Swarm is suitable for scenarios dealing with a large number of independent capabilities and instructions that are difficult to encode into a single prompt. It is not related to the Assistants API and is intended for educational purposes to explore multi-agent orchestration patterns.
## Links

- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) : The production-ready evolution of Swarm, featuring key improvements and actively maintained by the OpenAI team.
- [GitHub Documentation](https://docs.github.com) : Official documentation for GitHub, providing detailed information on using GitHub features and APIs.

## Topics

![](topics/Concept/Multi%20agent%20orchestration)

![](topics/Concept/Agent%20Handoffs)

![](topics/Concept/Swarm)