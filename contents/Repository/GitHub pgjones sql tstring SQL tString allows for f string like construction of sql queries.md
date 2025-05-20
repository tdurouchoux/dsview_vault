---
already_read: true
link: https://github.com/pgjones/sql-tstring
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Python
type: Content
upload_date: '2025-05-21'
---

https://github.com/pgjones/sql-tstring
## Summary

SQL-tString is a Python library that enables secure construction of SQL queries using a syntax similar to f-strings. It prevents SQL injection by allowing only identified variable parameters. Basic usage involves importing the library and using the `sql` method to create queries. 

Key features include:
- Safe inclusion of variables in SQL queries through syntax like `{a}`.
- Support for predefined table and column names via the `sql_context` function, which raises errors for invalid identifiers.
- Ability to handle optional parameters using the `Absent` value, allowing for conditional query modifications.
- Provides different parameter styles (e.g., `qmark`, `$`) which can be set globally.
- Compatible with Python versions 3.12 and 3.13, but optimally used with the t-string feature introduced in Python 3.14.

This library is particularly useful for Data Scientists and developers seeking to write cleaner, safer SQL queries.
## Links

- [PEP 750 – Literal String Interpolation](https://peps.python.org/pep-0750/) : This Python Enhancement Proposal introduces literal string interpolation as t-strings in Python 3.14.
- [Python Database API Specification v2.0](https://peps.python.org/pep-0249/#paramstyle) : This document describes the Python Database API and its paramstyle, which is relevant for the construction of SQL queries.
- [SQL-Tstring on PyPI](https://pypi.python.org/pypi/Sql-Tstring/) : The official Python Package Index page for SQL-Tstring, where you can find installation instructions and usage.
- [GitHub Code Search Documentation](https://docs.github.com/search-github/github-code-search/understanding-github-code-search-syntax) : Documentation on how to use GitHub's code search features, helpful for finding code snippets or examples.
- [GitHub Actions](https://github.com/features/actions) : Information about GitHub Actions, which can be useful for automating workflows in your code projects.

## Topics

![](topics/Library/SQL%20tString)

![](topics/Concept/SQL%20Injection%20Prevention)

![](topics/Concept/T%20Strings%20in%20Python)