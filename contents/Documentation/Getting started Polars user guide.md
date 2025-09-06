---
already_read: false
link: https://docs.pola.rs/user-guide/getting-started/
read_priority: 1
relevance: 0
source: null
tags:
- Data_Analysis
- Development_tool
type: Content
upload_date: '2024-01-18'
---

https://docs.pola.rs/user-guide/getting-started/
## Summary

The Polars user guide provides a comprehensive introduction to the Polars library, a DataFrame library implemented in Rust and available in Python. The guide covers the basics from installation to core functionalities, making it easy for new users to get started.

Key points include:

- **Installation**: Polars can be installed via pip for Python or cargo for Rust.
- **Reading & Writing**: Polars supports various file formats (CSV, JSON, Parquet) and cloud storage/databases. Examples are provided for creating, writing, and reading dataframes.
- **Expressions and Contexts**: Polars uses expressions for data transformations, which can be used within different contexts like `select`, `with_columns`, `filter`, and `group_by`. These contexts allow for selecting, manipulating, filtering, and aggregating data.
- **Complex Queries**: Contexts and expressions can be chained to create more complex queries.
- **Combining DataFrames**: Polars provides tools for joining and concatenating dataframes, with examples for left outer joins and vertical concatenation.

The guide also mentions additional sections for more detailed exploration of expressions, contexts, and other advanced features.
## Links

- [Polars DataFrame API Reference (Rust)](https://docs.pola.rs/api/rust/dev/polars/frame/struct.DataFrame.html) : This link points to the Rust API reference for the DataFrame struct in Polars, providing detailed information about methods and functionalities available for DataFrame manipulation in Rust.
- [Polars DataFrame API Reference (Python)](https://docs.pola.rs/api/python/stable/reference/dataframe/index.html) : This link points to the Python API reference for DataFrame manipulation in Polars, detailing methods and functionalities available for DataFrame operations in Python.

## Topics

![](topics/Library/Polars)