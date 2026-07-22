---
type: Concept
---

Context compression refers to the process of reducing the size of input data (e.g., text, code, logs, or RAG chunks) sent to LLMs to minimize token usage without sacrificing critical information. This technique is essential for optimizing costs and performance in LLM-based applications. Methods include reversible compression, content-aware routing, AST-based code compression, and live-zone compression, which selectively compresses only new or dynamic portions of the input while preserving static or previously compressed segments.