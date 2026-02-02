---
already_read: false
link: https://blog.sshh.io/p/how-i-use-every-claude-code-feature
read_priority: 5
relevance: 0
source: Data Elixir
tags:
- Development_tool
- AI_agent
type: Content
upload_date: '2025-12-08'
---

https://blog.sshh.io/p/how-i-use-every-claude-code-feature
## Summary

**Key Points and Takeaways:**

- **CLAUDE.md**: The most important file for using Claude Code effectively. It serves as the agent's "constitution" and should be treated as a high-level, curated set of guardrails and pointers. It should start small, document what Claude is getting wrong, and avoid bloating the context window.

- **Context Management**: Use /clear for simple reboots and the “Document & Clear” method to create durable, external “memory” for complex tasks. Don't trust auto-compaction.

- **Custom Slash Commands**: Use slash commands as simple, personal shortcuts, not as a replacement for building a more intuitive CLAUDE.md and better-tooled agent.

- **Custom Subagents**: Custom subagents are a brittle solution. Give your main agent the context (in CLAUDE.md) and let it use its own Task/Explore(...) feature to manage delegation.

- **Resume, Continue, & History**: Use claude --resume and claude --continue to restart sessions and uncover buried historical context.

- **Hooks**: Use hooks to enforce state validation at commit time (block-at-submit). Avoid blocking at write time—let the agent finish its plan, then check the final result.

- **Planning Mode**: Always use the built-in planning mode for complex changes to align on a plan before the agent starts working.

- **Skills**: Skills are the right abstraction. They formalize the “scripting”-based agent model, which is more robust and flexible than the rigid, API-like model that MCP represents.

- **MCP (Model Context Protocol)**: Use MCPs that act as data gateways. Give the agent one or two high-level tools (like a raw data dump API) that it can then script against.

- **Claude Code SDK**: The Claude Code SDK is a powerful, general-purpose agent framework. Use it for batch-processing code, building internal tools, and rapidly prototyping new agents before you reach for more complex frameworks.

- **Claude Code GHA**: The Claude Code GitHub Action (GHA) is a powerful feature that turns Claude Code into a core, auditable, and self-improving part of your engineering system.

- **settings.json**: Your settings.json is a powerful place for advanced customization. Use it to configure proxy settings, timeouts, API keys, and permissions.

- **Conclusion**: CLI-based agents like Claude Code are powerful tools for data scientists. The only way to learn is to dive in and experiment with the advanced features.
## Links

- [Claude Code Sub-agents](https://docs.claude.com/en/docs/claude-code/sub-agents) : Documentation on Claude Code Sub-agents, a feature that allows for context management by delegating tasks to specialized agents.
- [Claude Code Skills](https://docs.claude.com/en/docs/claude-code/skills) : Documentation on Claude Code Skills, a feature that formalizes the scripting-based agent model for more robust and flexible agent interactions.
- [Claude Code Hooks](https://docs.claude.com/en/docs/claude-code/hooks) : Documentation on Claude Code Hooks, a feature that allows for the enforcement of state validation at commit time and provides feedback on suboptimal agent actions.
- [Claude Code SDK](https://docs.claude.com/en/api/agent-sdk/overview) : Documentation on the Claude Code SDK, a powerful tool for building entirely new agents for both coding and non-coding tasks.
- [Claude Code GitHub Action](https://github.com/anthropics/claude-code-action) : GitHub repository for the Claude Code GitHub Action, a feature that allows for the operationalization of Claude Code within a GitHub Actions workflow.

## Topics

![[topics/Concept/Claude md]]

![[topics/Concept/Subagents]]

![[topics/Concept/Hooks]]

![[topics/Concept/Agent Skills]]

![[topics/Tool/Claude SDK]]

![[topics/Tool/Claude Code GitHub Action GHA]]

![[topics/Tool/Claude Code]]

![[topics/Concept/Model Context Protocol MCP]]