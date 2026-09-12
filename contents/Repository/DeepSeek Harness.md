---
already_read: true
link: https://deepseek.com/harness/en/
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- AI_agent
- Development_tool
type: Content
upload_date: '2026-09-12'
---

https://deepseek.com/harness/en/

## Summary

DeepSeek Harness is a modular, plugin-based framework for building and customizing AI agents, now in developer preview with full source code access.

**Core concept**
- Agent = Model + Harness, where the harness enables real-world interaction via plugins.

**Architecture**
- Built on the Cordis kernel, which manages plugin mounting, unmounting, and dependencies.
- Every capability (models, tools, skills, sessions, sandboxes, storage, loops, scheduling, UI) is a plugin.
- Plugins communicate via Cordis services and events.

**Key features**
- Fully configurable: swap or extend any capability without modifying the source code.
- Every run is traceable via an append-only session log (system prompts, reasoning, tool calls/results, subagent scheduling, context injections).
- Trajectory view allows inspection, resuming, forking, searching, and replaying of event streams.

**Runtime modes**
- **Standard mode**: Full toolset (file editing, shell, search, skills, planning, goals, subagents, workflows).
- **Code mode**: Standard mode capabilities exposed via a TypeScript SDK for multi-step tool orchestration.
- **Minimal mode**: Two-tool agent (persistent bash, `str_replace_editor`) for model benchmarking.
- **Creator mode**: Standard mode + runtime inspection, plugin testing, and preset-authoring tools.

**Getting started**
- Quick start: `npx @deepseek-ai/dsh web` or clone the [GitHub repo](https://github.com/deepseek-ai/deepseek-harness).
- Open-source (MIT license), with evolving core plugins and APIs.

## Links

- [DeepSeek Harness GitHub Repository](https://github.com/deepseek-ai/deepseek-harness) : Official GitHub repository for DeepSeek Harness, an open-source agent harness framework where every capability is implemented as a plugin. Includes source code, setup instructions, and documentation for developers to build, customize, and extend agent capabilities.
- [Cordis Plugin System GitHub Repository](https://github.com/cordiverse/cordis) : GitHub repository for Cordis, the plugin system underlying DeepSeek Harness. Cordis manages plugin mounting, dependencies, and inter-plugin communication, enabling modular and composable agent architectures.
- [DeepSeek Harness Quick Start Guide](https://deepseek-harness.github.io/deepseek-harness/en/guide/quickstart) : Quick start guide for DeepSeek Harness, providing step-by-step instructions to install, configure, and run the framework. Includes examples of different runtime modes (Standard, Code, Minimal, Creator) and plugin-based customization.
- [DeepSeek Harness Plugin Ecosystem](https://github.com/topics/dsh-plugin) : GitHub topic page aggregating community and official plugins for DeepSeek Harness (DSH). Useful for discovering reusable plugins to extend agent capabilities such as models, tools, skills, and UI components.


## Topics

![[topics/Platform/DeepSeek Harness]]

![[topics/Library/Cordis]]

![[topics/Tool/dsh]]

![[topics/Concept/Plugin based Architecture]]

![[topics/Concept/Runtime Modes]]

![[topics/Concept/Agent Harness]]