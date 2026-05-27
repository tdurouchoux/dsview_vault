---
already_read: true
link: https://github.com/Nutlope/hallmark
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Development_tool
type: Content
upload_date: '2026-05-27'
---

https://github.com/Nutlope/hallmark
## Summary

**Hallmark** is an anti-AI-slop design tool for Claude Code, Cursor, and Codex, ensuring outputs don’t look AI-generated. Key features:

- **Four verbs**:
  - `build`: Generates new UI with a unique macrostructure, 22 themes, and 65+ slop-test gates.
  - `audit`: Scores existing code against anti-patterns (no edits).
  - `redesign`: Rebuilds structure while preserving content/brand.
  - `study`: Extracts design DNA (macrostructure, typography, colors) from screenshots/URLs.

- **Outputs**: Self-contained HTML/CSS with unique macrostructures (no template reuse). Live demos at [usehallmark.com](https://www.usehallmark.com/).

- **Installation**:
  ```bash
  npx skills add nutlope/hallmark
  ```
  Or manually place files in:
  - Claude Code: `~/.claude/skills/hallmark/`
  - Cursor: `.cursor/rules/hallmark.mdc`
  - Codex: `~/.codex/skills/hallmark/` (personal) or `.codex/skills/hallmark/` (project).

- **License**: MIT. Rule-set in `SKILL.md`; examples in `docs/recipes.md` and `docs/study-examples.md`.
## Links

- [Hallmark Live Demo Site](https://www.usehallmark.com) : The official live demo site for Hallmark, showcasing examples of generated designs across various themes and briefs. It provides a visual representation of the tool's capabilities and output quality.
- [Hallmark Design Examples - Tally (SaaS)](https://www.usehallmark.com/examples/tally/) : A specific example of a Hallmark-generated design for a SaaS product named 'Tally.' It demonstrates the tool's ability to create modern-minimal designs tailored to specific use cases.
- [Hallmark Design Examples - Wayfare (Travel)](https://www.usehallmark.com/examples/wayfare/) : A specific example of a Hallmark-generated design for a travel-related website named 'Wayfare.' It highlights the tool's versatility in adapting to different industries and aesthetic preferences.
- [Hallmark Design Examples - BananaStudio (Studio)](https://www.usehallmark.com/examples/bananastudio/) : A specific example of a Hallmark-generated design for a creative studio named 'BananaStudio.' It showcases the tool's ability to produce playful and unique designs.
- [Hallmark Design Examples - Hyperlane (Dev Infrastructure)](https://www.usehallmark.com/examples/hyperlane/) : A specific example of a Hallmark-generated design for a dev infrastructure company named 'Hyperlane.' It demonstrates the tool's capability to create professional and technical designs.

## Topics

![[topics/Concept/Anti AI slop Design]]

![[topics/Tool/Hallmark Design Skill]]

![[topics/Concept/Macrostructure]]

![[topics/Concept/Slop Test Gates]]

![[topics/Concept/Design DNA Extraction]]

![[topics/Platform/usehallmark com]]

![[topics/Concept/AI Assisted Development]]