---
already_read: false
link: https://ibis-project.org/posts/does-ibis-understand-sql/?ref=blef.fr
read_priority: 5
relevance: 0
source: Blef
tags:
- Data_Engineering
type: Content
upload_date: '2025-03-09'
---

https://ibis-project.org/posts/does-ibis-understand-sql/?ref=blef.fr
## Summary

Ibis is a dataframe library that interfaces with databases, allowing users to construct and execute queries without writing raw SQL. It does not "understand" SQL in the traditional sense but provides a standardized interface for database interactions. 

Key points include:

- **Expression Building**: Users create expressions using Ibis's API, which are represented as trees of `Expr` and `Node` objects. This differs from SQL's parsing and binding process.
  
- **Compilation**: Ibis compiles expressions to SQL using SQLGlot, a no-dependency SQL parser and transpiler. This transition allows Ibis to leverage SQLGlot's capabilities for SQL generation and optimization.

- **Execution**: Compiled SQL queries are executed against the chosen backend, with results returned in a user-friendly format, such as a pandas DataFrame.

- **SQL Integration**: Users can still execute raw SQL queries through methods like `Table.sql()` and `Backend.sql()`, which compile to SQLGlot expressions but do not provide the same level of detail in the expression tree.

Overall, Ibis simplifies data manipulation while maintaining the ability to execute SQL when necessary, making it a versatile tool for data scientists.
## Links

1. [SQLGlot](https://sqlglot.com/sqlglot.html) - A no-dependency SQL parser, transpiler, optimizer, and engine that powers SQL comprehension and generation capabilities in various tools.
2. [Apache Superset](https://github.com/apache/superset) - An open-source data visualization and exploration platform that can benefit from SQL comprehension technologies.
3. [SQL comprehension technologies](https://docs.getdbt.com/blog/sql-comprehension-technologies) - An article discussing the levels of SQL comprehension and the technologies involved.
4. [SQLMesh](https://github.com/TobikoData/sqlmesh) - A tool that utilizes SQL comprehension for managing data transformations and lineage.
5. [Ibis Project GitHub](https://github.com/ibis-project/ibis) - The official repository for the Ibis project, which provides a dataframe API for working with SQL databases.
## Topics

![](topics/Library/Ibis)

![](topics/Library/SQLGlot)

![](topics/Concept/Dataframe%20API)

![](topics/Concept/Expression%20Tree)