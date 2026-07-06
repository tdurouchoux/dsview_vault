---
already_read: true
link: https://twotimespi.dev/
read_priority: 0
relevance: 4
source: hugging face
tags:
- Development_tool
type: Content
upload_date: '2026-07-06'
---

https://twotimespi.dev/
## Summary

Tau is a Python-based educational coding agent designed to teach how coding agents are built. It emphasizes transparency by making every component visible and understandable, functioning like a textbook where users can observe model outputs, tool calls, session management, and terminal UI interactions in real-time.

Key technical points include:
- **Architecture**: Separates the agent's brain (reusable harness), environment (coding tools), and UI (frontend like TUI or print mode) to ensure modularity and reusability.
- **Agent Loop**: Manages messages, tools, transcript state, and sessions, with provider adapters converting model responses into provider-neutral events.
- **Educational Focus**: Small, layered packages (e.g., `tau_ai`, `tau_agent`, `tau_coding`) teach core concepts like tool execution, durable sessions, and slash commands.
- **Session Management**: Durable sessions stored in `~/.tau/sessions` support resume, branching, and exports (JSONL/HTML).
- **Design Principles**: Events drive teachability, layers are kept small, and documentation evolves with implementation.

Inspired by Pi, Tau avoids hidden machinery, making it a practical tool for learning agent development while functioning as a real terminal agent. Installation via `uv tool install tau-ai` enables hands-on exploration.
## Links

- [Tau GitHub Repository](https://github.com/alejandro-ao/tau) : Official GitHub repository for Tau, an educational Python coding agent project focused on teaching the architecture, agent loops, and tool integrations of modular coding agents. Contains source code, documentation, and resources for building provider-neutral coding agents.

## Topics

![[topics/Concept/Agentic Coding]]

![[topics/Library/Textual]]

![[topics/Concept/Provider Neutral Streaming Interfaces]]

![[topics/Concept/Durable Execution]]

![[topics/Concept/Agent Loop]]

![[topics/Concept/Terminal User Interface TUI]]