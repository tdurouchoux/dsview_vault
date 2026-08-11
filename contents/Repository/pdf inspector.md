---
already_read: true
link: https://github.com/firecrawl/pdf-inspector
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2026-08-04'
---

https://github.com/firecrawl/pdf-inspector

## Summary

pdf-inspector is a high-performance Rust library for classifying and extracting text from PDFs without OCR, with bindings for Python, Node.js, and WebAssembly.

**Core capabilities**
- Classifies PDFs as TextBased, Scanned, ImageBased, or Mixed in ~10-50ms with confidence scores.
- Extracts position-aware text with font info, X/Y coordinates, and multi-column reading order.
- Converts to clean Markdown with headings, lists, code blocks, tables, bold/italic, URLs, and page breaks.
- Detects tables via rectangle-based and heuristic methods, handling financial tables and continuations.
- Supports CID fonts (ToUnicode CMap decoding), UTF-16BE/UTF-8/Latin-1 encodings, and RTL text.
- Flags broken font encodings for OCR fallback.
- Single document load shared between detection and extraction to avoid redundant I/O.

**Performance (opendataloader-bench, 200 PDFs, M4 Pro)**
- Overall score: **0.875** (highest), Reading Order: **0.915**, Tables: **0.814**, Speed: **0.470s** (fastest).
- Outperforms liteparse (0.873), opendataloader (0.831), pymupdf4llm (0.735), and markitdown (0.589).

**Bindings & CLI**
- Python, Node.js, WebAssembly, and Rust APIs with similar interfaces.
- CLI tools: `pdf2md` (convert to Markdown) and `detect-pdf` (classification only).
- CLI options: JSON output, raw Markdown, compact mode, page breaks, page selection, and layout analysis.

**Architecture**
- Detector: Fast classification via xref/page tree parsing and content stream sampling.
- Extractor: Fonts, content streams, XObjects, links, and layout analysis (columns, tables).
- Markdown converter: Font stats, preprocessing, conversion, classification, and postprocessing.
- Shared document load between detection and extraction.

**Classification strategies**
- `EarlyExit`: Stops on first non-text page (default).
- `Full`: Scans all pages.
- `Sample(n)`: Samples `n` distributed pages.
- `Pages(vec)`: Scans specific pages.

**Markdown detection rules**
- Headings: Font size tiers (0.5pt clustering).
- Bold/italic: Font name patterns.
- Lists: Bullet (`*`, `-`, `●`), numbered (`1.`), letter (`a.`) patterns.
- Code blocks: Monospace fonts and keyword detection.
- Tables: Rectangle-based + heuristic alignment.
- URLs, hyphenation, captions, sub/superscript, drop caps, dot leaders.

**Use case**
- Smart PDF routing: Classify (~20ms), extract locally if TextBased (~150ms), else send to OCR (2-10s).

**Technical details**
- Pure Rust, no ML models, single dependency (`lopdf`).
- Browser WebAssembly with embedded CMaps, no server round trip.
- MIT licensed.

## Links

- [pdf-inspector on PyPI](https://pypi.org/project/pdf-inspector/) : The Python Package Index (PyPI) page for pdf-inspector, providing installation instructions, package metadata, and usage details for Python users.
- [pdf-inspector on crates.io](https://crates.io/crates/pdf-inspector) : The Rust package registry page for pdf-inspector, offering installation instructions, version history, and dependency details for Rust users.
- [pdf-inspector on npm](https://www.npmjs.com/package/@firecrawl/pdf-inspector) : The Node.js package registry page for pdf-inspector, including installation instructions, version details, and usage examples for Node.js developers.
- [OpenDataLoader Benchmark Corpus](https://github.com/opendataloader-project/opendataloader-bench) : A benchmark corpus used to evaluate pdf-inspector's performance against other PDF parsing tools, including metrics for reading order, table detection, and speed.
- [pdf-inspector Benchmark Results](https://github.com/firecrawl/opendataloader-bench/tree/abi/pdf-parser-benchmark-results) : Detailed benchmark results and reproducible data for pdf-inspector, including parser configurations, per-document predictions, and evaluator outputs for transparency and comparison.


## Topics

![[topics/Concept/Structured Data Extraction]]

![[topics/Library/MarkItDown]]

![[topics/Tool/Firecrawl]]

![[topics/Library/lopdf]]

![[topics/Library/pdf inspector]]

![[topics/Concept/Position aware text extraction]]

![[topics/Concept/PDF classification]]

![[topics/Dataset/opendataloader bench]]