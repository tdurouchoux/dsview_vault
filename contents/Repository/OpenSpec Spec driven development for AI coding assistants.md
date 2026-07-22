---
already_read: true
link: https://github.com/Fission-AI/OpenSpec/
read_priority: 0
relevance: 3
source: null
tags:
- Development_tool
type: Content
upload_date: '2026-07-22'
---

https://github.com/Fission-AI/OpenSpec/
## Summary

OpenSpec is a spec-driven development (SDD) framework for AI coding assistants, emphasizing fluid, iterative, and scalable workflows. It enables structured collaboration between humans and AI by defining requirements in plain Markdown before coding begins. Key features include:

- **Workflow**: Uses slash commands (e.g., `/opsx:propose`, `/opsx:apply`) to guide AI through planning, implementation, and review phases.
- **Specs**: Requirements are stored in `specs/` folders as Markdown files with scenarios (e.g., "WHEN... THEN...").
- **Stores**: Beta feature for cross-repo planning, enabling shared specs across teams.
- **Philosophy**: Lightweight, adaptable, and tool-agnostic (supports 30+ AI assistants, including GitHub Copilot, Claude, and Codex).
- **Comparison**: Lighter than GitHub’s Spec Kit, more flexible than AWS’s Kiro, and more structured than ad-hoc AI coding.
- **Installation**: Requires Node.js 20.19.0+. Use `npm install -g @fission-ai/openspec@latest` and `openspec init` to start.
- **Model Support**: Recommends high-reasoning models (e.g., Codex 5.5, Opus 4.7) for best results.
- **Telemetry**: Anonymous usage stats collected (opt-out available).

Docs cover setup, workflows, and advanced features like multi-language support and customization. The project is MIT-licensed and encourages contributions via PRs for small fixes or proposals for larger changes.
## Links

- [OpenSpec Official Website](https://openspec.dev/) : The official website for OpenSpec, providing comprehensive documentation, guides, and resources about Spec-driven development (SDD) for AI coding assistants.
- [Spec Kit by GitHub](https://github.com/github/spec-kit) : A GitHub repository for Spec Kit, which provides tools and extensions for specification-driven development. This is directly compared to OpenSpec in the content.
- [NPM Package for OpenSpec](https://www.npmjs.com/package/@fission-ai/openspec) : The NPM package page for OpenSpec, which allows users to install and use OpenSpec in their projects.

## Topics

![[topics/Concept/AI Assisted Development]]

![[topics/Tool/OpenSpec]]

![[topics/Concept/Context Engineering]]

![[topics/Platform/Stores OpenSpec Stores]]

![[topics/Concept/Spec Driven Development SDD]]