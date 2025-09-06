---
already_read: true
link: https://fugue-tutorials.readthedocs.io/index.html
read_priority: 0
relevance: 0
source: null
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2024-09-25'
---

https://fugue-tutorials.readthedocs.io/index.html
## Summary

Fugue is a framework that simplifies distributed computing by minimizing code and optimizing execution across Spark, Dask, and Ray. It ports Python, Pandas, and SQL code to these backends, ensuring consistency and efficiency.

Key features include:
- **Fugue API**: Simplifies distributed computing with minimal code.
- **FugueSQL**: A SQL-like interface for Pandas, Spark, and Dask.
- **Extensions**: Various integrations with backends like Ibis, Polars, DuckDB, and cloud providers.
- **Applications**: Use cases include testing PySpark applications, distributed machine learning, and natural language processing.

Fugue compares favorably to other tools:
- **Spark, Dask, Ray**: Fugue simplifies their usage and bridges local testing to large-scale execution.
- **PySpark Pandas, Modin**: Fugue doesn't aim to replace Pandas but uses it for business logic.
- **dbt**: Fugue supports both SQL and Python, unlike dbt which confines users to SQL.
- **DuckDB, Ibis, Polars**: Fugue integrates with these tools, ensuring consistency and extending capabilities.

Installation is straightforward via pip, with backend engines installed separately. Tutorials can be run interactively using mybinder or Docker.
## Links

- [Fugue with Polars](https://fugue-tutorials.readthedocs.io/tutorials/integrations/backends/polars.html) : This link provides information on how to integrate Fugue with Polars, a high-performance DataFrame library in Rust and Python.
- [Fugue with BigQuery](https://fugue-tutorials.readthedocs.io/tutorials/integrations/warehouses/bigquery.html) : This link provides information on how to integrate Fugue with BigQuery, a cloud data warehouse by Google.
- [Fugue GitHub Repository](https://github.com/fugue-project/fugue) : This link leads to the official GitHub repository of Fugue, where you can find the source code, contribute to the project, and report issues.

## Topics

![](topics/Library/Fugue)

![](topics/Library/FugueSQL)

![](topics/Concept/Distributed%20Computing)