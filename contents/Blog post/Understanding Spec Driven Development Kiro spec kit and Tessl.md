---
already_read: false
link: https://martinfowler.com/articles/exploring-gen-ai/sdd-3-tools.html
read_priority: 5
relevance: 0
source: Data Elixir
tags:
- AI_agent
- Development_tool
type: Content
upload_date: '2026-03-14'
---

https://martinfowler.com/articles/exploring-gen-ai/sdd-3-tools.html
## Summary

**Summary:**

- **Spec-Driven Development (SDD)** is an emerging approach in AI-assisted coding where a "spec" is written before code, serving as the source of truth for both humans and AI.
- SDD has multiple implementation levels: spec-first, spec-anchored, and spec-as-source.
- A spec is a structured, behavior-oriented artifact written in natural language that guides AI coding agents.
- Evaluating SDD tools is time-consuming and challenging, especially for brownfield codebases.
- Three SDD tools were explored: Kiro, spec-kit, and Tessl Framework, each with different workflows and approaches.
  - **Kiro** is spec-first, with a simple workflow of Requirements → Design → Tasks.
  - **Spec-kit** is more customizable and uses a constitution as its memory bank, but may only be spec-first.
  - **Tessl Framework** aspires to be spec-anchored and is exploring spec-as-source, where the spec is the main artifact edited by humans.
- Observations and questions about SDD tools include:
  - One workflow may not fit all problem sizes.
  - Reviewing markdown files can be tedious compared to reviewing code.
  - AI may not always follow instructions, leading to a false sense of control.
  - Effectively separating functional from technical spec is challenging.
  - The target user for SDD tools is unclear.
  - Spec-as-source may combine the downsides of MDD and LLMs: inflexibility and non-determinism.
- The term "spec-driven development" is not well-defined and is already semantically diffused.
- While spec-first approaches are valuable, the real-world usefulness of SDD tools and their potential to amplify existing challenges like review overload and hallucinations remain uncertain.
## Links

- [Kiro](https://kiro.dev/) : Kiro is a tool for spec-driven development, guiding users through a structured workflow for requirements, design, and tasks using markdown documents.
- [Spec-kit](https://github.com/github/spec-kit/blob/main/spec-driven.md) : Spec-kit is GitHub's version of SDD, providing a CLI for setting up workspaces and interacting via slash commands in coding assistants, with a focus on a constitution-based workflow.
- [Tessl Framework](https://docs.tessl.io/introduction-to-tessl/quick-start-guide-tessl-framework) : Tessl Framework is a tool for spec-driven development that aims for a spec-anchored approach, allowing specs to be the main artifact maintained and edited, with code generated from these specs.

## Topics

![[topics/Concept/Spec Driven Development SDD]]

![[topics/Tool/Kiro]]

![[topics/Tool/Tessl Framework]]