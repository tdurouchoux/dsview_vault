---
already_read: true
link: https://claude.com/blog/introducing-dynamic-workflows-in-claude-code
read_priority: 0
relevance: 4
source: Data Points
tags:
- Large_Language_Model
type: Content
upload_date: '2026-06-01'
---

https://claude.com/blog/introducing-dynamic-workflows-in-claude-code
## Summary

Claude Code now supports **dynamic workflows**, enabling AI agents to autonomously handle complex, multi-step tasks end-to-end. Key features:

- **Parallel subagents**: Runs tens to hundreds of agents in parallel for tasks like bug hunts, migrations, or security audits.
- **Verification**: Checks results before submission, reducing errors.
- **Long-running tasks**: Handles workflows spanning hours/days, with progress saved for interruptions.
- **Adversarial validation**: Agents refute findings to improve accuracy.
- **Use cases**: Codebase-wide bug fixes, framework migrations (e.g., Bun’s Zig-to-Rust port in 11 days), security hardening, and refactoring.

**Availability**: Research preview in CLI, Desktop, VS Code extension (Max/Team/Enterprise), and APIs (Bedrock, Vertex AI, Microsoft Foundry). Enterprise admins can enable/disable workflows.

**Getting started**:
- Max/Team plans: Enabled by default (ask Claude to create a workflow or enable *ultracode* setting).
- Enterprise: Admins must enable (via settings).

**Note**: Higher token usage; start with scoped tasks. Confirmation required for first workflow run.
## Links

- [Claude Code Dynamic Workflows Documentation](https://code.claude.com/docs/en/workflows) : Official documentation for dynamic workflows in Claude Code, explaining how to use and configure this feature for handling complex tasks.
- [Claude Code Settings and Configuration](https://code.claude.com/docs/en/settings) : Details about the settings and configuration options available in Claude Code, including the 'ultracode' setting mentioned in the content.
- [Claude Code Overview](https://code.claude.com/docs/en/overview) : Overview documentation of Claude Code, which likely includes general information about its features and capabilities.
- [Claude Code API Pricing](http://claude.com/pricing#api) : Information about the pricing for using Claude Code via the API, including details about dynamic workflows availability for Max, Team, and Enterprise plans.

## Topics

![[topics/Concept/Agentic and Dynamic Workflows]]

![[topics/Platform/Microsoft Azure AI Foundry]]

![[topics/Tool/Claude Code]]

![[topics/Platform/Amazon Bedrock]]

![[topics/Platform/Vertex AI]]