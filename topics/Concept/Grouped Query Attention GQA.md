---
type: Concept
---

Grouped Query Attention (GQA) is an attention mechanism used in transformer-based models as a more computationally and parameter-efficient alternative to Multi-Head Attention (MHA). In GQA, multiple attention heads share the same key and value projections, reducing the number of key and value computations. This grouping decreases the total number of parameters and memory bandwidth usage during inference, leading to improved efficiency without significantly affecting modeling performance. GQA has been shown to perform comparably to standard MHA in terms of LLM performance, making it a popular choice in modern large language models.