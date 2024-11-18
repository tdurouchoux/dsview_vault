---
already_read: true
link: https://bnm3k.github.io/blog/duckdb-jit-udfs-numba
read_priority: 4
source: null
tags:
- Data_Engineering
- Python
type: Content
upload_date: '2024-10-12'
---

https://bnm3k.github.io/blog/duckdb-jit-udfs-numba
## Summary

DuckDB allows for the extension of its functionality through user-defined functions (UDFs), which can be particularly useful when built-in functions are insufficient. The article demonstrates how to compute the haversine distance between geographical points using both Python-native and JIT-compiled UDFs with Numba.

Key points include:

- **Python-Native UDFs**: A custom haversine function is defined in Python, but performance is limited due to Python interpreter overhead.
  
- **Numba JIT Compilation**: Numba can be used to JIT compile the haversine function, resulting in slight performance improvements (23.443 seconds vs. 26.7 seconds for the native version).

- **Vectorized UDFs**: To further enhance performance, vectorized UDFs are introduced, which process inputs and outputs as vectors, reducing overhead. The vectorized JIT version achieves a significant performance boost (2.998 seconds).

- **Comparison with Rust**: A Rust-based vectorized UDF performs slightly better than the Numba version (2.566 seconds).

- **Pure SQL Approach**: A SQL-based method for calculating haversine distance is the fastest, taking only 347.9 milliseconds.

- **Exporting to Numpy**: DuckDB can export datasets to Numpy for client-side computation, which is faster than vectorized UDFs but still slower than pure SQL.

- **CUDA Support**: Numba also supports CUDA for GPU acceleration, yielding competitive performance (1.803 seconds).

The article concludes with a summary of benchmarking results, highlighting the efficiency of pure SQL and the advantages of using vectorized UDFs for performance-critical applications.
## Links

1. [Numba Documentation](https://numba.readthedocs.io/en/stable/user/5minguide.html) - A quick guide to using Numba, a just-in-time compiler for Python that accelerates numerical functions.
2. [DuckDB Python UDFs](https://duckdb.org/2023/07/07/python-udf.html) - Documentation on extending DuckDB's functionality with user-defined functions in Python.
3. [Use Numba to work with Apache Arrow in pure Python](https://uwekorn.com/2018/08/03/use-numba-to-work-with-apache-arrow-in-pure-python.html) - A guide on integrating Numba with Apache Arrow for efficient data processing.
4. [Haversine Formula](https://en.wikipedia.org/wiki/Haversine_formula) - Wikipedia page explaining the haversine formula, which calculates distances between points on a sphere.
5. [Hyperfine](https://github.com/sharkdp/hyperfine) - A command-line benchmarking tool to measure the execution time of commands, useful for performance testing.
## Topics

![](topics/Library/DuckDB)

![](topics/Library/Numba)

![](topics/Concept/User%20Defined%20Functions%20UDFs)

![](topics/Concept/Vectorized%20UDFs)

![](topics/Concept/Haversine%20Distance)