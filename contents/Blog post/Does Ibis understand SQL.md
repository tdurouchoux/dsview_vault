---
already_read: false
link: https://ibis-project.org/posts/does-ibis-understand-sql/
read_priority: 5
relevance: 0
source: Blef
tags:
- Data_Analysis
type: Content
upload_date: '2025-03-09'
---

https://ibis-project.org/posts/does-ibis-understand-sql/
## Summary

Ibis is a data analysis tool that provides a dataframe API for working with databases, supporting multiple backends like ClickHouse, Apache Flink, and Starburst Galaxy. It doesn't inherently understand SQL but translates user queries into SQLGlot expressions for execution. The process involves building an expression, compiling it, and executing the compiled expression on the chosen backend. Ibis can handle SQL strings through methods like Table.sql() and Backend.sql(), but it only understands the output schema, not the inner structure of the SQL. The library is designed to be composable and works with various data ecosystems, offering capabilities similar to those of SQL comprehension tools.
## Links

- [SQLGlot Documentation](https://sqlglot.com/sqlglot.html) : SQLGlot is a no-dependency SQL parser, transpiler, optimizer, and engine. It’s a widely-used open-source project that powers the SQL comprehension and generation capabilities of tools like SQLMesh, Apache Superset, and Dagster.
- [SQLGlot GitHub Repository](https://github.com/tobymao/sqlglot) : The GitHub repository for SQLGlot, a SQL parser, transpiler, optimizer, and engine.
- [Ibis Project GitHub Repository](https://github.com/ibis-project/ibis) : The GitHub repository for the Ibis project, a Python data analysis toolkit that works with databases.

## Topics

![](topics/Library/SQLGlot)

![](topics/Library/Ibis)