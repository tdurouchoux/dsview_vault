---
already_read: true
link: https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f
read_priority: 0
relevance: 5
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-04-17'
---

https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f
## Summary

Core idea: Replace raw RAG retrieval with a persistent, LLM-maintained wiki that accumulates, cross-references, and updates knowledge incrementally. The wiki is a structured artifact between you and raw sources, not just indexed chunks.

Architecture: 3 layers — immutable raw sources (documents, images), LLM-generated wiki (markdown pages with summaries, entities, cross-links), and a schema file (e.g. CLAUDE.md) that defines workflows, conventions, and page formats. The schema is the key configuration.

Operations:
- Ingest: Drop a new source, LLM reads it, updates 10-15 wiki pages (summary, entities, index, log), and discusses key takeaways with you. Can be one-by-one or batched.
- Query: Ask questions against the wiki. LLM searches index, reads pages, synthesizes answers with citations, and can file new explorations back into the wiki.
- Lint: Periodically ask LLM to health-check the wiki (contradictions, stale claims, orphans, missing pages). Keeps knowledge consistent as it grows.

Key files:
- index.md: Catalog of wiki pages with links, summaries, and metadata. Updated on every ingest. Used by LLM to find relevant pages during query.
- log.md: Chronological append-only record of ingests, queries, lint passes. Parseable with simple tools (e.g. grep "^## \[" log.md).

Optional tooling:
- Local search engine (e.g. qmd) for larger wikis.
- CLI tools for linting, indexing, or search.
- Obsidian plugins (Dataview, Marp) for dynamic tables, slide decks, and better navigation.

Why it works:
- Humans are bad at wiki maintenance (updating cross-links, summaries, contradictions). LLMs don’t get bored and can touch 15 files in one pass.
- The wiki compounds — cross-references exist, contradictions are flagged, synthesis reflects everything you’ve read.
- Human job: curate sources, ask good questions, think about meaning. LLM job: everything else (summarizing, cross-referencing, filing).

Contexts: Personal knowledge tracking, deep research, reading books, business/team wikis, competitive analysis, trip planning.

Note: This is an abstract pattern, not a specific implementation. Directory structure, page formats, tooling will depend on your domain, preferences, and LLM of choice. Everything mentioned is optional and modular — pick what’s useful, ignore what isn’t.
## Links

- [OmegaWiki: An LLM-Powered Knowledge Base](https://github.com/skyllwt/OmegaWiki) : A GitHub repository for OmegaWiki, an actively maintained LLM-powered knowledge base with structured entities, edges, and bilingual support (English and Chinese). It includes 23 Claude Code skills covering the full research lifecycle and is designed for end-to-end knowledge synthesis and expansion.
- [ai-memex-cli: A Lightweight, Agent-Agnostic CLI for LLM-Wiki](https://github.com/zelixag/ai-memex-cli) : A lightweight, agent-agnostic CLI tool that implements the LLM-Wiki pattern. It handles mechanical correctness (file structure, frontmatter, linting) while delegating semantic correctness to the LLM agent. Supports universal agent integration, native slash commands, session distillation, and built-in web fetching.
- [llm-wiki-go: An Obsidian-Friendly Markdown Wiki for Go Codebases](https://github.com/olegiv/llm-wiki-go) : A prototype implementation of the LLM-Wiki pattern for Go codebases. It compiles raw documentation into a structured wiki with automated contradiction detection and structural linting. Includes a wikilint CLI for enforcing invariants like no orphan pages or broken links.
- [Synthadoc: A Structured LLM-Wiki Implementation with Human-in-the-Loop](https://github.com/axoviq-ai/synthadoc) : A structured implementation of the LLM-Wiki pattern using JSON schemas, source URL pinning, and confidence scoring. Features automated contradiction detection, human-in-the-loop review for low-confidence updates, and a focus on maintaining consistency between wiki pages and source documents.
- [SwarmVault: A Local-First LLM-Wiki Tool with Multi-Agent Support](https://github.com/swarmclawai/swarmvault) : A local-first, provider-agnostic tool for building and maintaining LLM-Wikis. Supports 16+ agent integrations, interactive graph viewers, bulk ingest/resume, and cross-file call graphs. Designed for scalability and resilience in knowledge management.

## Topics

![[topics/Concept/Personal Knowledge Management PKM]]

![[topics/Concept/Structured Knowledge Bases]]

![[topics/Tool/Obsidian]]

![[topics/Concept/Knowledge Compounding]]

![[topics/Concept/Contradiction Detection]]

![[topics/Concept/Agent Based Knowledge Curation]]

![[topics/Concept/Hybrid Search]]

![[topics/Concept/Local First Architecture]]