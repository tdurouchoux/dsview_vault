---
already_read: true
link: https://pi.dev/
read_priority: 0
relevance: 4
source: null
tags:
- Development_tool
type: Content
upload_date: '2026-05-18'
---

https://pi.dev/
## Summary

Pi is a minimal, terminal-based coding harness designed for customization. It supports four modes: interactive, print/JSON, RPC, and SDK. Users can adapt Pi to their workflows via extensions, skills, prompt templates, and themes, sharing these as Pi packages via npm or git. Key features include:

- **Model Flexibility**: Supports 15+ providers (e.g., Anthropic, OpenAI, Ollama) with mid-session switching.
- **Session Management**: Tree-structured history with branching, filtering, and export options (HTML/GitHub gist).
- **Context Engineering**: Project-specific instructions (AGENTS.md, SYSTEM.md), customizable compaction, and dynamic context injection.
- **Steering & Modes**: Submit messages mid-run (steering/follow-up) and generate scripts via print mode.
- **Extensibility**: Build or install extensions (TypeScript modules) for features like sub-agents, plan mode, or MCP integration.
- **Primitives Over Features**: Core is minimal; users build custom workflows (e.g., DOOM extension).

Install via `curl`, `npm`, `pnpm`, or `bun`. Community resources: GitHub (issues/features), Discord (discussion), and docs. MIT License.
## Links

- [Pi Coding Agent - Extensions Documentation](https://github.com/earendil-works/pi/tree/main/packages/coding-agent#extensions) : Official documentation for creating and using extensions in Pi. Extensions allow users to add custom tools, commands, keyboard shortcuts, and UI tweaks, aligning with Pi's 'primitives, not features' philosophy.
- [Pi Coding Agent - Skills Documentation](https://github.com/earendil-works/pi/tree/main/packages/coding-agent#skills) : Guide to 'skills' in Pi—capability packages with instructions and tools loaded on-demand. Skills enable progressive disclosure and modular workflows.
- [Pi Coding Agent - Models Configuration](https://github.com/earendil-works/pi/tree/main/packages/coding-agent/docs/models.md) : Documentation on configuring and switching between 15+ AI providers (e.g., Anthropic, OpenAI, Groq) and models dynamically during sessions.
- [Pi Coding Agent - RPC Mode Documentation](https://github.com/earendil-works/pi/tree/main/packages/coding-agent/docs/rpc.md) : Technical guide for using Pi in RPC mode, enabling JSON protocol integration with non-Node applications. Useful for embedding Pi in other systems.
- [OpenClaw - Real-World Pi Integration Example](https://github.com/OpenClaw/OpenClaw) : A real-world example of Pi embedded in an application (OpenClaw) via the SDK. Demonstrates how to integrate Pi programmatically for custom workflows.

## Topics

![[topics/Tool/Pi Coding Agent]]

![[topics/Concept/Context Window Management]]

![[topics/Concept/Tree Structured Session History]]

![[topics/Library/Pi Packages]]

![[topics/Platform/npm]]

![[topics/Concept/Dynamic Context Injection]]

![[topics/Concept/Progressive Disclosure]]