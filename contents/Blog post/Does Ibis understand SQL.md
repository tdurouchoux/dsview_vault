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

Ibis is a dataframe library that interfaces with databases, allowing users to work with data without writing handcrafted SQL queries. It provides a standardized interface for database operations and supports various backends like ClickHouse, Apache Flink, Starburst Galaxy, and more.

**Key Points:**

1. **Expression Building**: Ibis uses a dataframe API to build expressions. These expressions are represented as a tree of `Expr` and `Node` objects, which can be visualized or pretty-printed.

2. **Compiling Expressions**: Ibis compiles expressions to SQL using SQLGlot, a SQL parser, transpiler, optimizer, and engine. This transition to SQLGlot occurred in Ibis 9.0.

3. **Executing Compiled Expressions**: The compiled SQL is executed using the database connection associated with the backend instance. The results are then massaged into a desired format, such as a pandas DataFrame.

4. **SQL Understanding**: Ibis does not inherently understand SQL but comprehends what users are trying to achieve through its standardized interface. It can handle SQL strings via `Table.sql()` and `Backend.sql()`, but these methods do not provide the same level of detail as the dataframe API.

5. **SQLGlot Integration**: Ibis leverages SQLGlot for SQL generation, benefiting from its capabilities like column-level lineage. The integration with SQLGlot enhances Ibis's ability to compile and execute SQL queries efficiently.

6. **Backend Support**: Ibis supports a wide range of backends, including Amazon Athena, BigQuery, ClickHouse, Dask, Databricks, and more. This flexibility allows users to work with various database systems seamlessly.

7. **Visualization and Analytics**: Ibis supports integration with visualization tools like Altair, Plotly, and Streamlit, enabling users to create visualizations and perform analytics on their data.

8. **Extending Ibis**: Users can extend Ibis by writing custom functions, using SQL strings, and working with streaming data. The library provides a robust set of APIs for these purposes.

In summary, Ibis is a powerful tool for data manipulation and analysis, offering a high-level interface for working with databases and supporting a wide range of backends. Its integration with SQLGlot enhances its SQL generation capabilities, making it a versatile choice for data scientists and analysts.
## Links

- [SQLGlot](https://sqlglot.com/sqlglot.html) : SQLGlot is a no-dependency SQL parser, transpiler, optimizer, and engine. It’s a widely-used open-source project that powers the SQL comprehension and generation capabilities of tools like SQLMesh, Apache Superset, and Dagster.
- [SQLMesh](https://github.com/TobikoData/sqlmesh) : SQLMesh is a data management platform that leverages SQLGlot for SQL comprehension and generation.
- [Apache Superset](https://github.com/apache/superset) : Apache Superset is a modern data exploration and visualization platform that uses SQLGlot for SQL parsing and transpilation.

## Topics

![](topics/Library/SQLGlot)

![](topics/Library/Ibis)