---
already_read: true
link: https://github.com/headroomlabs-ai/headroom
read_priority: 0
relevance: 5
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-07-22'
---

https://github.com/headroomlabs-ai/headroom
## Summary

Headroom is a **context compression tool** for AI agents/LLMs that reduces token usage by **60-95% for JSON data** and **15-20% for coding agents** while preserving answer accuracy. It supports multiple modes: **library (Python/TypeScript)**, **proxy (zero-code integration)**, **agent wrapping**, and **MCP server**.

**Key features:**
- **Content-aware compressors**: SmartCrusher (JSON), CodeCompressor (AST for code), Kompress-v2-base (text).
- **Reversible compression (CCR)**: Originals cached locally for retrieval.
- **Cross-agent memory**: Shared context across tools (Claude, Codex, Grok, etc.).
- **Output token reduction**: Trims model responses (e.g., ceremony code, redundant thinking).
- **Agent compatibility**: Works with 15+ tools (Claude Code, Cursor, Copilot, etc.).

**Performance:**
- **Real-world savings**: 92% for code search, 73% for GitHub triage.
- **Accuracy preserved**: GSM8K (87%), TruthfulQA (+3%), SQuAD v2 (97% compression).

**Deployment:**
- Install via `uv`, `pip`, or Docker.
- Configure with `headroom wrap`, `headroom proxy`, or inline SDK.
- Supports **output shaping** (verbosity control) and **learning from failures** (`headroom learn`).

**Use cases:** Ideal for teams using AI agents daily, needing cross-agent memory, or reversible compression. Not suited for sandboxed environments.

**Tech stack:** Python/Rust backend, TypeScript SDK, HuggingFace model (Kompress-v2-base).

**License:** Apache 2.0. Managed enterprise support available.
## Links

- [Headroom Documentation - Architecture](https://headroom-docs.vercel.app/docs/architecture) : Detailed documentation explaining the architecture of Headroom, including its components like CacheAligner, ContentRouter, and compression mechanisms.
- [Headroom Documentation - How Compression Works](https://headroom-docs.vercel.app/docs/how-compression-works) : Explains the internal workings of Headroom's compression pipeline, including SmartCrusher, CodeCompressor, and Kompress-v2-base models.
- [Headroom Documentation - Installation Guide](https://headroom-docs.vercel.app/docs/installation) : Step-by-step guide for installing Headroom, including prerequisites, installation methods (CLI, Python, TypeScript), and troubleshooting tips.
- [Headroom Documentation - MCP Tools](https://headroom-docs.vercel.app/docs/mcp) : Documentation for Headroom's MCP (Model Context Protocol) server integration, enabling seamless interaction with MCP-compatible clients.
- [Headroom Documentation - Benchmarks](https://headroom-docs.vercel.app/docs/benchmarks) : Performance benchmarks showcasing Headroom's token reduction efficiency across various workloads like code search, SRE debugging, and JSON compression.

## Topics

![[topics/Library/headroom]]

![[topics/Concept/Context Compression]]

![[topics/Concept/Reversible Compression CCR]]

![[topics/Concept/Content Aware Compression]]

![[topics/Concept/Cross Agent Memory]]

![[topics/Concept/Output Token Reduction]]

![[topics/Tool/Model Context Protocol MCP Server]]

![[topics/Concept/Agent Wrapping]]

![[topics/Concept/Live Zone Compression]]