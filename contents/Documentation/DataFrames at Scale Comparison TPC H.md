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
   - **Spark**: Performs poorly at small scales and is outperformed by Dask at large scales. It is noted for its complexity and configuration challenges.
   - **Dask**: Performs reliably across all scales, outperforming Spark and being more robust than Polars and DuckDB. It is praised for its ease of use and flexibility.
   - **DuckDB**: Performs well at all scales but is limited by its inability to scale beyond a single VM. It is easy to use and performs well on SQL queries.
   - **Polars**: Excels at small scales locally but struggles with large-scale and cloud data processing. It is noted for its rapid development and potential for future improvements.

2. **Comparisons Between Projects**:
   - **Dask vs. Spark**: Dask is generally faster and more robust across scales.
   - **Polars vs. DuckDB**: DuckDB outperforms Polars on single-machine local computations and in the cloud.
   - **Polars vs. Pandas and Dask**: Polars outperforms Dask locally on small data, while Dask outperforms Polars in the cloud on large data.
   - **Dask vs. DuckDB**: DuckDB performs better for smaller datasets, while Dask performs better on larger datasets.

3. **Recommendations**:
   - **Local + Small Data**: Choose DuckDB or Polars.
   - **Local + Big Data**: Choose Dask or DuckDB.
   - **Cloud at 1 TB or Less**: Choose Dask or DuckDB.
   - **Cloud at Large Scale**: Choose Dask or Spark.

4. **Experimental Details**:
   - The benchmarks were run on various scales locally and on the cloud using AWS EC2 instances.
   - Specific configurations and optimizations were applied to each project to ensure fair comparisons.
   - The document provides code snippets and configuration details for running the benchmarks with each project.

5. **Bias and Expert Input**:
   - The authors acknowledge their bias towards Dask and note that they sought input from experts in other systems to ensure fair performance comparisons.

Overall, the document provides a detailed analysis of the performance and suitability of different DataFrame projects for various scales and use cases, highlighting the strengths and weaknesses of each.
## Links

- [Polars Benchmarks](https://pola.rs/posts/benchmarks/) : Polars benchmarks for the latest performance details.
- [DuckDB TPC-H Extension](https://duckdb.org/docs/extensions/tpch.html) : DuckDB TPC-H extension documentation for generating TPC-H benchmark data.
- [Polars GitHub TPC-H](https://github.com/pola-rs/tpch/tree/c306449be4cbf81506ef3845aef98897206190f7) : Polars GitHub repository for TPC-H benchmarks and related code.
- [Dask Official Website](https://www.dask.org/) : Official website for Dask, providing information and resources on Dask.

## Topics

![](topics/Library/Dask)

![](topics/Library/Apache%20Spark)

![](topics/Concept/TPC%20H%20Benchmark)

![](topics/Concept/DataFrame)

![](topics/Concept/Serverless%20Functions)

![](topics/Concept/Prefect)

![](topics/Library/DuckDB)

![](topics/Library/Polars)