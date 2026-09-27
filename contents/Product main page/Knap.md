---
already_read: true
link: https://knap.md/
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Development_tool
type: Content
upload_date: '2026-09-27'
---

https://knap.md/

## Summary

Knap is a lightweight template language for converting structured data into Markdown with logic, variables, and filters.

**Core features**
- Inline variables (e.g., `{{ title }}`) inject data into Markdown.
- Filters (e.g., `| blockquote`, `| sort`, `| table`) transform values and formatting.
- Conditional logic (`{% if %}`) and iteration over arrays.
- YAML frontmatter generation with custom properties.

**Usage**
- CLI: `npx knap render template.md --data data.json --output note.md`.
- API: Install via `npm install knap` (or pnpm/yarn/bun).
- Integrations: Used in Obsidian (Web Clipper, Importer) and other tools.

**Technical details**
- Open-source (MIT license).
- Supports extended Markdown syntax (e.g., wikilinks for Obsidian).

## Links

- [Knap GitHub Repository](https://github.com/obsidianmd/knap) : The official GitHub repository for Knap, an open-source template language that turns data into Markdown using logic, variables, and filters. This is the primary source for documentation, usage examples, and contributions.
- [Obsidian Web Clipper](https://obsidian.md/clipper) : A tool by Obsidian that allows saving web pages to Markdown with customizable templates, leveraging Knap for templating. This is directly related to Knap's use case in web clipping.
- [Obsidian Importer](https://community.obsidian.md/plugins/obsidian-importer) : A plugin for Obsidian that converts data from various apps and file formats to portable Markdown files, which can be integrated with Knap for further templating.
- [Knapping (Wikipedia)](https://en.wikipedia.org/wiki/Knapping) : An article explaining the process of knapping, the inspiration behind the name 'Knap.' This provides context for the tool's naming and its metaphorical connection to shaping data into structured formats.


## Topics

![[topics/Library/Knap]]

![[topics/Tool/Obsidian]]