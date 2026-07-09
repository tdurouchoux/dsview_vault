---
already_read: true
link: https://github.com/run-llama/ParseBench
read_priority: 0
relevance: 4
source: null
tags:
- Natural_Language_Processing
type: Content
upload_date: '2026-07-09'
---

https://github.com/run-llama/ParseBench
## Summary

ParseBench is a benchmark for evaluating document parsing tools, focusing on their ability to convert PDFs into structured output usable by AI agents. It tests ~2,000 human-verified pages from real enterprise documents across five capability dimensions: tables, charts, content faithfulness, semantic formatting, and visual grounding. Each dimension targets specific failure modes critical for production workflows.

Key features:
- Leaderboard ranks tools by overall score (e.g., LlamaParse Agentic leads at 84.88%).
- Dataset hosted on HuggingFace, covering diverse document types (insurance, finance, government).
- Deterministic, rule-based evaluation (no LLM-as-a-judge).
- Supports 90+ parsing pipelines (e.g., LlamaParse, Google Gemini, AWS Textract).

Technical highlights:
- Evaluation metrics include GTRM (tables), ChartDataPointMatch (charts), and custom scores for other dimensions.
- CLI commands for running benchmarks, generating reports, and comparing tools (e.g., `parse-bench run`, `parse-bench compare`).
- Output includes HTML reports, CSV/JSON exports, and aggregation dashboards.
- API keys required only for the parsing tool being evaluated.

Project structure emphasizes modularity (inference, evaluation, analysis) and extensibility (e.g., adding new tools via `/integrate-pipeline`). Citation available for the accompanying paper (arXiv:2604.08538).
## Links

- [ParseBench Official Leaderboard](https://parsebench.ai) : The official leaderboard for ParseBench, showcasing the top-performing document parsing tools and their scores across five capability dimensions. This is critical for benchmarking and comparing tools discussed in the ParseBench repository.
- [ParseBench Dataset on HuggingFace](https://huggingface.co/datasets/llamaindex/ParseBench) : The HuggingFace dataset page for ParseBench, containing ~2,000 human-verified pages from real enterprise documents. This dataset is used for evaluating document parsing tools and is essential for reproducibility and further research.
- [ParseBench Paper on arXiv](https://arxiv.org/abs/2604.08538) : The arXiv paper titled 'ParseBench: A Document Parsing Benchmark for AI Agents,' which provides detailed insights into the benchmark's methodology, evaluation dimensions, and findings. This is highly relevant for academic and technical reference.

## Topics

![[topics/Concept/Document Parsing Benchmark]]

![[topics/Concept/Structured Data Extraction]]

![[topics/Concept/Chart Data Extraction]]

![[topics/Concept/Content Faithfulness]]

![[topics/Concept/Semantic Formatting Preservation]]

![[topics/Concept/Grounding]]

![[topics/Concept/Rule Based Evaluation]]

![[topics/Dataset/ParseBench Dataset]]

![[topics/Tool/TEDS Metric]]

![[topics/Concept/AI Agent Workflows]]