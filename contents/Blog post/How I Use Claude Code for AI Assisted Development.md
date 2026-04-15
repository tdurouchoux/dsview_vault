---
already_read: true
link: https://boristane.com/blog/how-i-use-claude-code/
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Development_tool
type: Content
upload_date: '2026-04-15'
---

https://boristane.com/blog/how-i-use-claude-code/
## Summary

The author outlines a structured workflow for using Claude Code, emphasizing separation of planning and execution to improve code quality and efficiency. Key phases include:

1. **Research**: Deeply analyze the codebase to understand its intricacies, documenting findings in `research.md` to prevent system-breaking changes. Requires explicit instructions (e.g., "deeply," "intricacies") to ensure thoroughness.

2. **Planning**: Generate a detailed `plan.md` outlining implementation steps, code snippets, and trade-offs. Use external reference implementations to guide planning. The author prefers manual `.md` plans over built-in modes for better control.

3. **Annotation Cycle**: Iteratively refine the plan by adding inline notes (e.g., correcting assumptions, rejecting approaches) until the plan aligns with project needs. This cycle (1–6 rounds) ensures the plan reflects domain knowledge and constraints.

4. **Implementation**: Execute the plan with a standardized prompt ("implement it all") while enforcing constraints (e.g., no unnecessary comments, continuous typechecking). Progress is tracked via a granular todo list in the plan.

5. **Feedback & Iteration**: Provide terse corrections during implementation (e.g., "wider," "revert everything") and revert changes if scope drifts. Reference existing code patterns for precision.

6. **Driver’s Seat**: Actively steer decisions by cherry-picking, trimming scope, or overriding technical choices during planning/implementation. Claude handles mechanical execution.

**Key Principles**:
- Never let AI write code without a reviewed plan.
- Persistent artifacts (`research.md`, `plan.md`) act as shared context.
- Single long sessions maintain context and efficiency.
- Separate creative (planning) and mechanical (implementation) work.

The workflow prioritizes control, context preservation, and iterative refinement to avoid common pitfalls of AI-assisted coding (e.g., misaligned implementations, scope creep).
## Links

- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code) : Official documentation for Claude Code, providing detailed information about its features, usage, and capabilities. This is highly relevant as the blog post discusses workflows and best practices for using Claude Code effectively.

## Topics

![[topics/Concept/AI Assisted Development]]

![[topics/Concept/Code Annotation Cycle]]

![[topics/Concept/Persistent Artifact Driven Development]]

![[topics/Concept/Task Decomposition]]

![[topics/Concept/Terse Correction Feedback]]

![[topics/Concept/Context Window Management]]

![[topics/Tool/Claude Code]]