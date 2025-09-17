---
already_read: false
link: https://docs.coiled.io/blog/tpch.html
read_priority: 1
relevance: 0
source: null
tags:
- Data_Analysis
- Data_Visualization
type: Content
upload_date: '2024-09-04'
---

https://docs.coiled.io/blog/tpch.html
## Summary

The document presents a comprehensive comparison of DataFrame projects (Apache Spark, Dask, DuckDB, and Polars) using TPC-H benchmarks across various scales and hardware architectures. Key findings include:

1. **Project Performance**:
   - **Spark**: Performs poorly at small scales and is outperformed by Dask at large scales. It requires significant configuration and has high CPU occupancy.
   - **Dask**: Robust and performs well across all scales, especially in the cloud. It is easier to configure and use compared to Spark.
   - **DuckDB**: Performs well at all scales but is limited by its inability to scale beyond a single VM. It is easy to use and excels in SQL queries.
   - **Polars**: Excels at small scales locally but struggles with large multi-table joins and cloud data readers. It is rapidly developing but not yet stable at large scales.

2. **Comparisons**:
   - **Dask vs. Spark**: Dask is generally faster and more robust across scales.
   - **Polars vs. DuckDB**: DuckDB outperforms Polars on single-machine local computations, but Polars is preferred for its Pythonic feel and flexibility.
   - **Polars vs. Pandas and Dask**: Polars beats Dask locally on small data, while Dask outperforms Polars in the cloud on large data.
   - **Dask vs. DuckDB**: DuckDB performs better for smaller datasets, while Dask is better for larger datasets.

3. **Recommendations**:
   - **Local + small data**: Choose DuckDB or Polars.
   - **Local + big data**: Choose Dask or DuckDB.
   - **Cloud at 1 TB or less**: Choose Dask or DuckDB.
   - **Cloud at large scale**: Choose Dask or Spark.

4. **Experimental Details**:
   - Benchmarks were run on various scales locally and on the cloud using AWS EC2 instances.
   - Specific configurations and optimizations were applied for each project to ensure fair comparisons.
   - The document provides code snippets and configuration details for running the benchmarks.

5. **Bias and Limitations**:
   - The authors acknowledge their familiarity with Dask and collaboration with experts from other projects to ensure fair benchmarking.
   - The benchmarks are hardware-specific, and results may vary based on the environment.

Overall, the document provides a detailed analysis of the performance and suitability of different DataFrame projects for various use cases and scales.
## Links

- [Polars Benchmarks](https://pola.rs/posts/benchmarks/) : Polars benchmarks for the latest performance details.
- [TPC-H Data Generation Script](https://github.com/coiled/benchmarks/blob/13ebb9c72b1941c90b602e3aaea82ac18fafcddc/tests/tpch/generate_data.py) : Script used to generate TPC-H data for benchmarks.
- [Dask-Expr Issue](https://github.com/dask/dask-expr/issues/1065) : Issue tracking join order optimization in Dask-Expr.
- [Polars TPC-H Reference Implementations](https://github.com/pola-rs/tpch/tree/c306449be4cbf81506ef3845aef98897206190f7) : Reference implementations of TPC-H queries in Polars.
- [DuckDB TPC-H Extension](https://duckdb.org/docs/extensions/tpch.html) : DuckDB extension for generating TPC-H data.

## Topics

![](topics/Library/Apache%20Spark)

![](topics/Library/Dask)

![](topics/Concept/TPC%20H%20Benchmark)

![](topics/Concept/Coiled)

![](topics/Library/DuckDB)

![](topics/Library/Polars)