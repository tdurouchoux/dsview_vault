---
already_read: true
link: https://github.com/tobi/qmd
read_priority: 0
relevance: 4
source: null
tags:
- Data_Engineering
- Large_Language_Model
- Natural_Language_Processing
type: Content
upload_date: '2026-09-21'
---

https://github.com/tobi/qmd

## Summary

QMD is a local, hybrid search engine for markdown, docs, and transcripts that combines BM25, vector search, and LLM re-ranking for high-quality results.

**Core**
- Hybrid pipeline: BM25 (FTS5) + vector (sqlite-vec) + LLM reranking (Qwen3)
- Query expansion via fine-tuned 1.7B model (HyDE + dense variants)
- Reciprocal Rank Fusion (RRF) with position-aware blending (75%/60%/40% RRF weight for top 1-3/4-10/11+)
- Top-rank bonus (+0.05 for #1, +0.02 for #2-3) preserves exact matches
- Score ranges: 0.8-1.0 (high), 0.5-0.8 (moderate), 0.2-0.5 (some), 0.0-0.2 (low)

**Search Modes**
- `search`: BM25-only (fast)
- `vsearch`: Vector-only (semantic)
- `query`: Full hybrid pipeline (best quality)
- Typed sub-queries: `lex` (BM25), `vec` (vector), `hyde` (hypothetical document embeddings)

**Indexing**
- Smart chunking: ~900 tokens with 15% overlap, AST-aware for code (tree-sitter)
- Break points: headings (100-50), code blocks (80), horizontal rules (60), blank lines (20)
- Default models: embeddinggemma-300M (300MB), qwen3-reranker-0.6B (640MB), qmd-query-expansion-1.7B (1.1GB)
- Models cached in `~/.cache/qmd/models/` (GGUF via node-llama-cpp)

**CLI**
- Collection management: `add`, `list`, `remove`, `rename`, `include`/`exclude`
- Context: `add`/`rm`/`list` for path-based metadata
- Search: `--json`, `--files`, `--min-score`, `--filter` (metadata), `--intent`
- Output: CLI (colored, hyperlinks), JSON, CSV, MD, XML, files
- Editor links: `QMD_EDITOR_URI` template (VS Code, Cursor, Zed, Sublime)

**Integration**
- MCP server: `query`, `get`, `multi_get`, `status` tools
- HTTP transport: `POST /mcp`, `POST /query`, `GET /health`
- SDK: `createStore()`, `search()`, `get()`, `multiGet()`, `embed()`
- HTTP endpoints: `/mcp` (MCP), `/query` (structured search), `/health` (liveness)
- Origin/Host validation: `QMD_ALLOWED_ORIGINS`, `QMD_ALLOWED_HOSTS`

**Metadata Filtering**
- Frontmatter: `qmd.metadata` with user-defined keys (strings, numbers, booleans, arrays)
- Filter JSON AST: `and`/`or`/`not`, `eq`/`ne`/`gt`/`gte`/`lt`/`lte`, `in`/`nin`/`all`, `exists`
- Typed matching: no coercion, exact types

**Storage**
- SQLite: `~/.cache/qmd/index.sqlite` (collections, documents, FTS5, vectors, llm_cache)
- Project-local: `.qmd/index.yml` + `.qmd/index.sqlite` (via `qmd init`)

**Requirements**
- Node.js >= 22 or Bun >= 1.0.0
- macOS: `brew install sqlite` (for FTS5 extensions)
- GPU: `QMD_LLAMA_GPU` (auto/metal/vulkan/cuda/false), `QMD_FORCE_CPU=1`

**Benchmarking**
- `qmd bench` with fixture JSON (queries + expected files)
- Reports precision@k, recall, MRR, F1 for BM25, vector, hybrid, full pipelines

## Links

- [Tree-sitter: Parser Generator Tool and Incremental Parsing Library](https://tree-sitter.github.io/) : Tree-sitter is a parser generator tool and an incremental parsing library that can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. It is used in QMD for AST-aware chunking of code files (e.g., TypeScript, JavaScript, Python, Go, Rust) to improve search result quality by chunking at function, class, and import boundaries instead of arbitrary text positions.


## Topics

![[topics/Library/node llama cpp]]

![[topics/Model/EmbeddingGemma]]

![[topics/Model/qwen3 reranker 0 6b]]

![[topics/Model/qmd query expansion 1 7B]]

![[topics/Concept/Reciprocal Rank Fusion RRF]]

![[topics/Concept/AST aware chunking]]

![[topics/Concept/Model Context Protocol MCP]]

![[topics/Tool/tree sitter]]

![[topics/Tool/sqlite vec]]

![[topics/Concept/GGUF]]