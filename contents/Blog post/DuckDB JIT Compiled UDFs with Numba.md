---
already_read: true
link: https://bnm3k.github.io/blog/duckdb-jit-udfs-numba
read_priority: 4
source: Aucune
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

1. **Python-Native UDFs**: A custom haversine function is defined in Python, but performance is limited due to interpreter overhead.

2. **Numba for Performance**: Numba is introduced to JIT compile the Python function, resulting in a slight performance improvement (23.443 seconds vs. 26.7 seconds).

3. **Vectorized UDFs**: To further enhance performance, vectorized UDFs are implemented, which process inputs and outputs as vectors, reducing overhead. The vectorized JIT version achieves a significant performance boost (2.998 seconds).

4. **Comparison with Rust**: A Rust-based vectorized UDF is also tested, showing competitive performance (2.566 seconds).

5. **Pure SQL Approach**: A pure SQL implementation of the haversine distance calculation outperforms all other methods, taking only 347.9 milliseconds.

6. **Exporting to Numpy**: DuckDB can export datasets to Numpy for computation, which is faster than vectorized UDFs but still not as fast as pure SQL.

7. **CUDA Support**: Numba supports CUDA for GPU acceleration, yielding similar performance to the OpenMP CPU version.

The article concludes with benchmarking results, highlighting the efficiency of pure SQL and the potential of vectorized UDFs for performance optimization in DuckDB.
## Links

1. [Numba](https://numba.readthedocs.io/en/stable/) - Official documentation for Numba, a just-in-time compiler for Python that accelerates numerical functions.
2. [Arrow](https://arrow.apache.org/) - Apache Arrow is a cross-language development platform for in-memory data, which is used for zero-copy data interchange.
3. [A ~5 minute guide to Numba - Numba Documentation](https://numba.readthedocs.io/en/stable/user/5minguide.html) - A quick guide to get started with Numba, covering its basic features and usage.
4. [pure SQL-based approach](https://stackoverflow.com/a/72730460) - A StackOverflow discussion on implementing a pure SQL approach for calculating haversine distance, which outperforms other methods.
5. [From Waddle to Flying: Quickly expanding DuckDB’s functionality with Scalar Python UDFs - DuckDB Team](https://duckdb.org/2023/07/07/python-udf.html) - An article detailing how to enhance DuckDB's capabilities using Python UDFs.
## Topics

- [[topics/Library/DuckDB]]
- [[topics/Library/Numba]]
- [[topics/Concept/User-Defined Functions (UDFs)]]
- [[topics/Concept/Vectorized Data Processing]]
- [[topics/Concept/Arrow Format]]