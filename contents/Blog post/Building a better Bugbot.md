---
already_read: true
link: https://cursor.com/blog/building-bugbot
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- AI_agent
- Development_tool
type: Content
upload_date: '2026-02-01'
---

https://cursor.com/blog/building-bugbot
## Summary

Bugbot is a code review agent designed to analyze pull requests for logic bugs, performance issues, and security vulnerabilities. Initially, the project began with qualitative assessments and evolved into a more systematic approach using a custom AI-driven metric called the resolution rate. This metric measures the effectiveness of Bugbot by determining if bugs are resolved at PR merge time.

Key improvements and experiments include running multiple bug-finding passes in parallel with majority voting, rebuilding Git integration in Rust for faster and more reliable repository access, and adding Bugbot rules to support codebase-specific invariants. The resolution rate metric allowed for quantitative assessment and hill-climbing on quality, leading to significant improvements in Bugbot's performance.

A major breakthrough came with the switch to a fully agentic design, which allowed the agent to reason over the diff, call tools, and decide where to dig deeper. This approach required rethinking prompting strategies and opened up richer surfaces for experimentation. The agentic architecture also enabled more dynamic context management and toolset iteration.

Since its launch, Bugbot has reviewed over two million PRs per month for various customers and internal code at Cursor. Future plans include launching Bugbot Autofix in Beta, enabling Bugbot to run code to verify its own bug reports, and experimenting with an always-on version that continuously scans the codebase. The goal is to continuously improve Bugbot's performance and maintain code quality as AI development workflows scale.
## Links

- [Bugbot Documentation](https://cursor.com/docs/bugbot) : Official documentation for Bugbot, providing detailed information on how to use and configure the code review agent.
- [Blog Post on Dynamic Context Discovery](https://cursor.com/blog/dynamic-context-discovery) : A blog post discussing the dynamic context discovery features and improvements in Bugbot.

## Topics

![[topics/Tool/Bugbot]]

![[topics/Concept/Agentic Architecture]]

![[topics/Concept/Resolution Rate]]

![[topics/Concept/BugBench]]

![[topics/Concept/Hill Climbing]]