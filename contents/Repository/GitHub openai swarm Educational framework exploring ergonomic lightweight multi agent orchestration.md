---
already_read: true
link: https://github.com/openai/swarm/tree/main
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- AI_agent
type: Content
upload_date: '2024-10-15'
---

https://github.com/openai/swarm/tree/main
## Summary

Swarm is an educational framework developed by OpenAI for exploring lightweight multi-agent orchestration. It aims to simplify agent coordination and execution through two core abstractions: Agents and handoffs, facilitating scalable, real-world solutions without a steep learning curve. Swarm is not stateful between calls and runs primarily on the client. 

Key features include:
- **Agents**: These encapsulate instructions and functions, allowing for specific workflows or tasks.
- **Handoffs**: Agents can transfer execution to other Agents.
- **Function Calling**: Agents can directly call Python functions, enhancing flexibility.
- **Context Variables**: Allows agents to pass and update contextual information throughout interactions.
- **Streaming Support**: Enables real-time responses while processing interactions.

Swarm is now succeeded by the OpenAI Agents SDK, which provides production-ready features and maintenance. Users are encouraged to transition to the SDK for practical applications. The framework is easy to install via Python and includes various examples to assist users in implementation.
## Links

- [OpenAI API Reference - Streaming](https://platform.openai.com/docs/api-reference/streaming) : Provides documentation on how to use streaming capabilities with the OpenAI API.
- [OpenAI API Reference - Chat Create Messages](https://platform.openai.com/docs/api-reference/chat/create#chat-create-messages) : This link leads to the documentation for creating chat messages using the OpenAI API.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) : GitHub repository for OpenAI Agents, a production-ready SDK for multi-agent orchestration following the Swarm concepts.

## Topics

![](topics/Library/Swarm)

![](topics/Concept/Multi%20Agent%20Orchestration%20and%20Architecture)

![](topics/Platform/OpenAI%20Agents%20SDK)

![](topics/Concept/Agent%20Handoffs)

![](topics/Concept/Function%20Calling%20in%20Agents)