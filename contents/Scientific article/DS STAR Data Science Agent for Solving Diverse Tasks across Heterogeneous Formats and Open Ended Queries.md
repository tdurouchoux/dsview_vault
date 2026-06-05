---
already_read: false
link: https://arxiv.org/pdf/2509.21825
read_priority: 5
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
type: Content
upload_date: '2026-06-05'
---

https://arxiv.org/pdf/2509.21825
## Summary

DS-STAR is a specialized agent designed to automate data science workflows, addressing two key limitations of existing LLM-based agents: handling heterogeneous data formats and generating comprehensive research reports for open-ended queries. It operates through a multi-agent framework with distinct roles:

**Core Capabilities:**
1. **Data File Analysis**: Uses an analyzer agent to generate Python scripts that summarize diverse data formats (CSV, JSON, Excel, etc.), extracting essential properties like column names, data types, and metadata.
2. **Iterative Planning & Execution**: Employs a planner agent to create high-level steps, a coder agent to implement them as Python/SQL scripts, and a verifier agent (LLM-based judge) to assess plan sufficiency beyond mere code execution.
3. **Plan Refinement**: Uses a router agent to decide whether to add new steps or correct existing ones, with backtracking to remove erroneous steps.
4. **Debugging**: Incorporates a debugging agent to fix errors in generated scripts.
5. **Report Generation (DS-STAR+)**: For open-ended queries, decomposes the task into sub-questions, solves them using DS-STAR, and compiles a comprehensive report with citations.

**Key Technical Features:**
- Processes heterogeneous data formats (CSV, JSON, Excel, Markdown, etc.) by generating format-specific analysis scripts.
- Implements step-by-step planning with intermediate verification, improving adaptability to complex tasks.
- Uses retrieval mechanisms for large datasets to handle context window limitations.
- Supports both Python and SQL code generation.
- Achieves state-of-the-art performance on benchmarks like DABStep, KramaBench, and DA-Code, particularly excelling in hard-level tasks requiring multi-file processing.

**Performance Highlights:**
- Significantly outperforms baselines on DABStep (45.24% vs 41.01% hard-level accuracy).
- Generates preferred reports in over 88% of cases compared to DeepAnalyze.
- Demonstrates robustness in handling complex Excel files with multiple tables.

**Limitations & Future Work:**
- Current focus is on fully automated frameworks; extending to human-in-the-loop settings could enhance performance.
- The framework's effectiveness depends on the underlying LLM's capabilities, though it shows promising results with both proprietary and open-source models.
## Links


## Topics

![[topics/Concept/Multi Agent Systems]]

![[topics/Concept/Text to Python]]

![[topics/Concept/Data File Formats]]

![[topics/Concept/Iterative Refinement]]

![[topics/Concept/Data File Analyzer]]

![[topics/Concept/Plan Verification]]

![[topics/Concept/Open Ended Queries]]

![[topics/Concept/Data Retrieval]]

![[topics/Concept/Data Science Agent]]

![[topics/Concept/LLM as a Judge]]