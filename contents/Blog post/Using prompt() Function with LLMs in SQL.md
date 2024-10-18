---
already_read: true
link: https://motherduck.com/blog/sql-llm-prompt-function-gpt-models/?utm_source=substack&utm_medium=email
read_priority: 3
source: 'Data Science Weekly '
tags:
- Natural_Language_Processing
- Data_Engineering
type: Content
upload_date: '2024-10-18'
---

https://motherduck.com/blog/sql-llm-prompt-function-gpt-models/?utm_source=substack&utm_medium=email
## Summary

The prompt() function has been introduced to integrate small language models (SLMs) like OpenAI's gpt-4o-mini into SQL queries, allowing for advanced natural language processing directly within a SQL data warehouse. This function simplifies tasks such as text generation, summarization, and structured data extraction without needing separate infrastructure.

Key features include:
- Support for gpt-4o-mini and gpt-4o models, enabling bulk text summarization and structured output generation.
- The ability to apply the function to all rows in a table, significantly speeding up processing times compared to traditional methods.
- Structured output capabilities using parameters like struct and struct_descr, which define the expected output format and provide detailed descriptions for model guidance.

Use cases highlighted include:
1. **Text Summarization**: Efficiently summarizing text columns in datasets.
2. **Unstructured to Structured Data Conversion**: Extracting structured information such as topic, sentiment, and technologies mentioned in comments.

Practical considerations suggest testing on small samples first and recognizing that for certain tasks, traditional SQL methods may be more efficient. The prompt() function is currently in preview for users on the Free Trial or Standard Plan, with usage quotas in place to manage compute costs.
## Links

1. [gpt-4o-mini](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/) - Overview of the gpt-4o-mini model and its advancements in cost-efficient intelligence.
2. [text summarization](https://motherduck.com/docs/sql-reference/motherduck-sql-reference/ai-functions/prompt/#summarization) - Documentation on how to use the prompt() function for text summarization in SQL.
3. [structured data extraction](https://motherduck.com/docs/sql-reference/motherduck-sql-reference/ai-functions/prompt/#structured-data-extraction) - Guide on using the prompt() function for extracting structured data from unstructured text.
4. [OpenAI’s structured model outputs](https://openai.com/index/introducing-structured-outputs-in-the-api/) - Information on how OpenAI's structured model outputs work and their applications.
5. [DuckDB’s regex_extract](https://duckdb.org/docs/sql/functions/regular_expressions.html) - Documentation on the regex_extract function in DuckDB for efficient text extraction.
## Topics

- [[topics/Model/gpt-4o-mini]]
- [[topics/Model/gpt-4o]]
- [[topics/Concept/Unstructured to Structured Data Conversion]]
- [[topics/Concept/Bulk Text Summarization]]