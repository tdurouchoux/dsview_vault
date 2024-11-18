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

The blog post introduces the `prompt()` function, a new feature in MotherDuck that allows users to integrate small language models (SLMs) like OpenAI's gpt-4o-mini directly into SQL queries. This function simplifies the process of generating, summarizing, and extracting structured data from text without needing separate infrastructure.

Key points include:

- **Functionality**: The `prompt()` function supports bulk text summarization and structured data extraction, allowing for both single-row and multi-row processing.
- **Use Cases**: Examples include summarizing comments from Hacker News into Haikus and converting unstructured text into structured outputs (e.g., extracting topics, sentiment, and technologies).
- **Performance**: The function can handle multiple requests concurrently, significantly speeding up processing times compared to traditional methods.
- **Structured Outputs**: Users can specify output structures using parameters like `struct` and `struct_descr`, ensuring adherence to defined schemas.
- **Practical Considerations**: Users are advised to test on small samples first and consider the efficiency of SQL-based operations for certain tasks over LLMs.
- **Availability**: The `prompt()` function is in preview for users on the Free Trial or Standard Plan, with usage quotas in place to manage compute costs.

Overall, the `prompt()` function enhances the integration of LLMs with SQL, making advanced data processing more accessible.
## Links

1. [DuckDB SQL Reference - Prompt Function](https://motherduck.com/docs/sql-reference/motherduck-sql-reference/ai-functions/prompt/) - Comprehensive documentation on the prompt() function, including its usage and capabilities.
2. [Structured Outputs in OpenAI API](https://openai.com/index/introducing-structured-outputs-in-the-api/) - Information on how OpenAI's API supports structured outputs, relevant for understanding the integration with SQL.
3. [ACM SIGMOD Publication](https://dl.acm.org/doi/10.1145/3650203.3663334) - Research publication discussing advancements in data management, which may provide insights into the integration of LLMs with SQL.
4. [DuckDB Regular Expressions Documentation](https://duckdb.org/docs/sql/functions/regular_expressions.html) - Documentation on regular expressions in DuckDB, useful for understanding text processing capabilities.
5. [DuckDB Sample Data Queries - Hacker News](https://motherduck.com/docs/getting-started/sample-data-queries/hacker-news/) - Example queries using DuckDB with Hacker News data, demonstrating practical applications of SQL functions.
## Topics

![](topics/Model/gpt%204o%20mini)

![](topics/Model/gpt%204o)

![](topics/Concept/Unstructured%20Data%20Processing)

![](topics/Product/MotherDuck)