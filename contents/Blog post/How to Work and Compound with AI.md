---
already_read: true
link: https://eugeneyan.com//writing/working-with-ai/
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- AI_agent
type: Content
upload_date: '2026-05-23'
---

https://eugeneyan.com//writing/working-with-ai/
## Summary

To work effectively with AI, treat it like a collaborator: provide clear context, encode preferences as config, ensure easy verification, delegate tasks, and refine systems over time. Organize your workspace (e.g., `~/src`, `~/vault`) and use annotated indexes (`INDEX.md`, `CLAUDE.md`) to help AI navigate context. Split memory into facts (`~/vault`) and config (`~/.claude`). Define behavior, teaching style, and workflows in `~/.claude/CLAUDE.md`, splitting long configs into lazy-loaded guides or skills (markdown workflows triggered on demand). Bootstrap skills by refining tasks iteratively, using session transcripts for updates. Verify work via automated hooks (e.g., linting), tests, or LLM reviews, and delegate larger tasks by defining success criteria. Scale by running parallel sessions, monitoring progress (e.g., tmux emojis, stop-hook alerts), and closing loops by mining transcripts for config updates. Principles: context > config > verification > delegation > refinement. Applies to both AI and human teams. Start by having AI read this guide to apply it to your workflow.
## Links

- [Model Context Protocol Documentation](https://modelcontextprotocol.io/docs/getting-started/intro) : Documentation for the Model Context Protocol (MCP), relevant to connecting AI models to organizational context (e.g., Slack, Drive, Mail) for efficient retrieval and utilization.
- [Claude Code Memory System Documentation](https://code.claude.com/docs/en/memory#how-claude-md-files-load) : Documentation explaining how Claude Code's memory system works, particularly CLAUDE.md files that encode preferences, workflows, and personal taste as configuration for AI interactions.

## Topics

![[topics/Concept/AI Collaboration Workflow]]

![[topics/Concept/Context Management]]

![[topics/Concept/Agent Skills]]

![[topics/Concept/AI Verification and Self Correction Mechanisms]]

![[topics/Concept/Delegation in AI Workflows]]

![[topics/Concept/Persistent Memory in AI]]

![[topics/Concept/Taste as Configuration]]

![[topics/Concept/Parallel AI Sessions]]

![[topics/Concept/Transcript Mining]]