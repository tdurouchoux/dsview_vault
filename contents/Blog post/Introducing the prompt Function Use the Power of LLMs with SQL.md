---
already_read: true
link: https://motherduck.com/blog/sql-llm-prompt-function-gpt-models/
read_priority: 3
relevance: 0
source: 'Data Science Weekly '
tags:
- Large_Language_Model
type: Content
upload_date: '2024-10-18'
---

https://motherduck.com/blog/sql-llm-prompt-function-gpt-models/
## Summary

The blog introduces the `prompt()` function, enabling integration of small language models (SLMs) like OpenAI's gpt-4o-mini with SQL for generating, summarizing, and extracting structured data. This function allows users to perform operations like bulk text summarization and structured data generation directly within SQL queries, improving efficiency and reducing the need for separate infrastructure.

Key points include:
- The function supports both gpt-4o-mini and gpt-4 models.
- Users can apply it for bulk operations (e.g., summarization) across multiple rows and specify output structures using parameters like `struct` and `struct_descr`.
- Practical use cases include text summarization and converting unstructured data into structured outputs with specific fields (e.g., topic, sentiment).
- A warning is advised to test prompt-based use cases on smaller samples and consider SQL methods for specific tasks where they are more efficient.

The `prompt()` function is available in preview for MotherDuck users, with quotas for compute usage depending on the plan. Users are encouraged to explore and provide feedback on this new functionality.
## Links

- [DuckDB Documentation](https://duckdb.org/docs/sql/reference/motherduck-sql-reference/ai-functions/prompt/#structured-data-extraction) : Documentation on using the prompt() function in DuckDB for structured data extraction.
- [OpenAI's GPT-4o Mini Overview](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/) : Information about the gpt-4o-mini model and its advancements in cost-effective intelligence.
- [ACM SIGMOD Publication](https://dl.acm.org/doi/10.1145/3650203.3663334) : Research publication discussing advancements in data wrangling and the integration of SQL and LLMs.
- [DuckDB Regular Expressions Functions](https://duckdb.org/docs/sql/functions/regular_expressions.html) : Documentation on regular expressions functions in DuckDB, useful for text processing.
- [OpenAI Structured Outputs](https://openai.com/index/introducing-structured-outputs-in-the-api/) : Overview of structured outputs feature in OpenAI's API for better data handling.

## Topics

![](topics/Tool/prompt%20Function)

![](topics/Concept/Unstructured%20to%20Structured%20Data%20Conversion)

![](topics/Tool/DuckDB)

![](topics/Library/OpenAI%20Models)