---
already_read: true
link: https://github.com/pgjones/sql-tstring
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Data_Engineering
- Python
type: Content
upload_date: '2025-05-21'
---

https://github.com/pgjones/sql-tstring
## Summary

SQL-tString is a Python library that enables the construction of SQL queries using f-string-like syntax, while preventing SQL injection. Key features include:

1. **Basic Usage**: Variables can be inserted into SQL queries using `{variable}` syntax, which are then converted to SQL placeholders.
2. **Context Management**: The `sql_context` function allows for the validation of column and table names to prevent SQL injection.
3. **Rewriting Values**: Special values like `Absent`, `IsNull`, and `IsNotNull` can be used to modify the SQL query dynamically.
4. **Dialect Support**: Supports different SQL parameter styles (e.g., qmark, $, asyncpg) which can be set globally.
5. **Backward Compatibility**: Compatible with Python versions 3.12 and 3.13, using a slightly different syntax for non-t-string support.

The library is designed to make SQL query construction safer and more intuitive, leveraging Python's f-string capabilities while ensuring security.
## Links

- [SQL-tString Repository Commits](https://github.com/pgjones/sql-tstring/commits/main) : View the commit history of the SQL-tString repository on GitHub.
- [Python Enhancement Proposal 750](https://peps.python.org/pep-0750/) : Read about the Python Enhancement Proposal (PEP) 750, which introduced t-strings in Python 3.14.

## Topics

![[topics/Library/SQL tString]]