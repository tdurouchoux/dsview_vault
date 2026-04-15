---
already_read: true
link: https://code.claude.com/docs/en/memory
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Development_tool
type: Content
upload_date: '2026-04-15'
---

https://code.claude.com/docs/en/memory
## Summary

Claude Code uses two systems for persistent memory across sessions: **CLAUDE.md files** (user-written instructions) and **auto memory** (Claude's self-generated notes). Key points:

- **CLAUDE.md files**: Markdown files with instructions (coding standards, workflows, etc.). Can be scoped to projects, users, or organizations. Loaded at session start. Best practices: keep under 200 lines, use specific instructions, structure clearly, and split large files using imports or `.claude/rules/`.
- **Auto memory**: Claude saves learnings (debugging insights, preferences) in `~/.claude/projects/<project>/memory/`. Limited to first 200 lines or 25KB per session. Editable via `/memory` command.
- **Organization**: Use `.claude/rules/` for modular, path-specific rules. Managed policies (e.g., `/Library/Application Support/ClaudeCode/CLAUDE.md`) enforce org-wide rules.
- **Troubleshooting**: Check loaded files with `/memory`, ensure specificity in instructions, and avoid conflicts. Large `CLAUDE.md` files should be split.
## Links

- [Anthropic Research Publications](https://www.anthropic.com/research) : Anthropic's official research page featuring papers, articles, and updates on AI advancements relevant to Data Science trends and tools.
- [Anthropic Engineering Blog](https://www.anthropic.com/engineering) : Technical blog discussing challenges, solutions, and innovations in AI development, valuable for Data Scientists interested in AI engineering.
- [Anthropic Trust Center](https://trust.anthropic.com/) : Information about Anthropic's AI safety practices, responsible AI initiatives, and regulatory compliance, important for ethical AI development.
- [Anthropic Transparency Report](https://www.anthropic.com/transparency) : Details Anthropic's policies, practices, and commitments to transparency in AI development, useful for understanding the broader impact of AI technologies.
- [Anthropic Supported Countries](https://www.anthropic.com/supported-countries) : Lists countries where Anthropic's services are available, including regional restrictions, relevant for global Data Science contexts.

## Topics

![[topics/Concept/Context Window Optimization and Management]]

![[topics/Concept/Instruction Management Systems]]

![[topics/Tool/memory Command]]

![[topics/Concept/Persistent Memory in AI]]

![[topics/Concept/Path Specific Rules]]

![[topics/Concept/Managed Policies]]