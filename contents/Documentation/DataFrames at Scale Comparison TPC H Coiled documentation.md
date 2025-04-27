---
already_read: false
link: https://docs.coiled.io/blog/tpch.html
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2024-09-04'
---

https://docs.coiled.io/blog/tpch.html
## Summary

The document presents a benchmarking analysis of various DataFrame projects (Apache Spark, Dask, DuckDB, and Polars) using the TPC-H benchmark suite across different scales and hardware environments, both locally and in the cloud. 

Key findings include:

- No single project consistently outperforms the others; each has strengths and weaknesses depending on use cases and data sizes.
- **Performance Overview**:
  - **Spark** is reliable but generally the least efficient, especially at smaller scales (10 GB), where it can be significantly slower than other options.
  - **Dask** performs well across all scales and is robust, particularly in cloud environments, though slightly slower than DuckDB and Polars locally for small datasets.
  - **DuckDB** excels in local contexts, performs well with SQL queries but lacks scalability (limited to a single machine).
  - **Polars** shows excellent performance on smaller local datasets but struggles with larger datasets and complex queries in the cloud.

- **Usage Recommendations**:
  - For local small datasets, choose **DuckDB** or **Polars**.
  - For larger local datasets, opt for **Dask** or **DuckDB**.
  - For cloud datasets (up to 1 TB), **Dask** or **DuckDB** is preferable.
  - For larger scale cloud processing, **Dask** or **Spark** outperforms DuckDB and Polars.

- **Comparison Highlights**:
  - Dask tends to be faster and easier to configure than Spark.
  - DuckDB generally outperforms Polars on local computations, while increasing the scale favors Dask over DuckDB.
  - Significant configuration and tuning steps are necessary for optimal performance, especially with Spark, which proved to be cumbersome.

The document stresses that user needs, workload types, and deployment considerations play critical roles in selecting the appropriate technology.
## Links

- [DuckDB Official Site](https://duckdb.org/) : Official website for DuckDB, a database management system designed to support analytical queries.
- [Dask Official Site](https://www.dask.org/) : Official site for Dask, a flexible library for parallel computing in Python.
- [Coiled Documentation](https://docs.coiled.io/user_guide/index.html) : Documentation for Coiled, covering various features and usage guidelines for data processing in the cloud.
- [Polars Official Site](https://pola.rs/) : Official website for Polars, a fast DataFrame library implemented in Rust.
- [DuckDB TPC-H Extension](https://duckdb.org/docs/extensions/tpch.html) : Documentation for using the TPC-H benchmark extension in DuckDB.

## Topics

![](topics/Library/Dask)

![](topics/Tool/Spark)

![](topics/Library/DuckDB)

![](topics/Library/Polars)

![](topics/Concept/Benchmarking%20in%20Machine%20Learning)

![](topics/Concept/DataFrame)