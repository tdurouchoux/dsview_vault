---
already_read: true
link: https://fugue-tutorials.readthedocs.io/index.html
read_priority: 0
source: Aucune
tags:
- Data_Engineering
type: Content
upload_date: '2024-09-25'
---

https://fugue-tutorials.readthedocs.io/index.html
## Summary

Fugue Tutorials provide a comprehensive guide to using Fugue, a framework designed to simplify distributed computing with backends like Spark, Dask, and Ray. Key features include:

- **Quick Start**: Users can quickly learn to use Fugue and FugueSQL in just 10 minutes.
- **Core Concepts**: Tutorials cover essential functions such as `transform()`, type hinting, schema management, partitioning, execution engines, and data transformations.
- **Deep Dive**: Advanced topics include configurations, data validation, and the use of X-like objects.
- **FugueSQL**: A SQL-like interface that integrates with various backends, allowing users to leverage both SQL and Python.
- **Extensions**: Users can create custom components like processors and transformers.
- **Integrations**: Fugue supports various backends and cloud providers, facilitating seamless transitions from local to distributed environments.
- **Applications**: Use cases include testing PySpark applications, distributed machine learning, and natural language processing.
- **Comparison**: Fugue is compared to other frameworks like PySpark, dbt, and Polars, emphasizing its unique approach to minimizing framework-specific code and ensuring consistency across backends.

Installation is straightforward via pip, and users can run tutorials interactively using platforms like Binder or Docker.
## Links

1. [DuckDB documentation](https://duckdb.org/docs/guides/python/fugue) - Official documentation for DuckDB, which is a backend for Fugue, allowing users to prototype code in a local setting and scale out.
2. [BigQuery integration](https://fugue-tutorials.readthedocs.io/tutorials/integrations/warehouses/bigquery.html) - Documentation on how to integrate Fugue with Google BigQuery for data processing.
3. [Fugue](https://github.com/fugue-project/fugue) - The source code repository for Fugue, providing insights into its implementation and features.
4. [Why Pandas-like interfaces are sub-optimal for distributed computing](https://towardsdatascience.com/why-pandas-like-interfaces-are-sub-optimal-for-distributed-computing-322dacbce43) - An article discussing the limitations of using Pandas-like interfaces in distributed computing environments.
5. [Polars Integration](https://fugue-tutorials.readthedocs.io/tutorials/integrations/backends/polars.html) - Documentation on how to use Polars with Fugue for efficient data processing.
## Topics

- [[topics/Library/Fugue]]
- [[topics/Concept/FugueSQL]]
- [[topics/Concept/Distributed Computing and Training]]
- [[topics/Concept/Data Integration]]
- [[topics/Concept/Backend Engines]]