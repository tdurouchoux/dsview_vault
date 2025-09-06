---
already_read: true
link: https://github.com/pgjones/sql-tstring
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Development_tool
type: Content
upload_date: '2025-05-21'
---

https://github.com/pgjones/sql-tstring
## Summary

SQL-tString is a Python library that enables the construction of SQL queries using f-string-like syntax, specifically t-strings, while preventing SQL injection. Key features include:

1. **Basic Usage**: Variables can be inserted into SQL queries using `{variable}` syntax, with the library converting these to SQL placeholders and providing the values separately for safe execution.

2. **Context Management**: The `sql_context` function allows predefined column or table names to be used safely, raising errors if invalid names are provided.

3. **Rewriting Values**: Special values like `Absent`, `IsNull`, and `IsNotNull` can be used to conditionally include or exclude parts of the query or handle NULL values appropriately.

4. **Dialect Support**: Supports different SQL parameter styles (dialects), such as qmark (default) and asyncpg, which can be set globally.

5. **Backward Compatibility**: Compatible with Python versions 3.12 and 3.13, using a slightly different syntax for non-t-string support.

The library is designed to enhance SQL query construction in Python, making it safer and more flexible.
## Links

- [Python Enhancement Proposal 750](https://peps.python.org/pep-0750/) : This link points to the Python Enhancement Proposal 750, which introduces t-strings in Python 3.14. It is relevant to the content as the SQL-tString library leverages t-strings for constructing SQL queries.
- [Python Enhancement Proposal 249](https://peps.python.org/pep-0249/#paramstyle) : This link points to the Python Enhancement Proposal 249, which discusses the paramstyle (dialect) used in SQL-tString. It is relevant as it explains the different parameter styles supported by the library.

## Topics

![](topics/Library/SQL%20tString)