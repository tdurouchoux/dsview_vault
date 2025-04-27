---
already_read: false
link: https://docs.pola.rs/user-guide/getting-started/
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2024-01-18'
---

https://docs.pola.rs/user-guide/getting-started/
## Summary

The Polars user guide provides a comprehensive introduction to the Polars DataFrame library, emphasizing key features for data manipulation. Key points include:

- **Installation**: Polars can be installed via pip for Python or Cargo for Rust.
  
- **Data I/O**: Supports reading and writing various formats (CSV, JSON, Parquet) and integrates with cloud storage and databases.

- **Expressions and Contexts**: Central to Polars are expressions used for data transformation, with contexts such as `select`, `with_columns`, `filter`, and `group_by` helping to manipulate and analyze data.

  - **Select**: Used for selecting and manipulating columns.
  
  - **With_columns**: Adds new columns to a DataFrame.
  
  - **Filter**: Creates a new DataFrame based on conditions.
  
  - **Group_by**: Groups data for aggregation and analysis.

- **More Complex Queries**: Combines multiple contexts for intricate data queries.

- **Combining DataFrames**: Includes methods for joining (e.g., left joins) and concatenating DataFrames to expand data structures.

The guide also references advanced topics such as lazy evaluation, time series data handling, and optimizations in query processing, facilitating efficient data operations for users familiar with DataFrames.
## Links

- [Polars DataFrame Join Documentation](https://docs.pola.rs/api/python/stable/reference/dataframe/api/polars.DataFrame.join.html) : Documentation about the join functionality in Polars DataFrames.
- [Polars DataFrame Documentation](https://docs.pola.rs/api/rust/dev/polars/frame/struct.DataFrame.html) : Basic reference for the DataFrame struct in Polars.
- [Polars CSV Writer Documentation](https://docs.pola.rs/api/rust/dev/polars/prelude/struct.CsvWriter.html) : Documentation of the CsvWriter for writing DataFrames to CSV files.
- [Polars Filter Method Documentation](https://docs.pola.rs/api/python/stable/reference/dataframe/api/polars.DataFrame.filter.html) : Documentation on how to filter DataFrames in Polars.
- [Polars Group By and Aggregate](https://docs.pola.rs/api/python/stable/reference/dataframe/api/polars.DataFrame.group_by.html) : Documentation for performing group by operations and aggregations on Polars DataFrames.

## Topics

![](topics/Library/Polars)

![](topics/Concept/DataFrame%20operations)

![](topics/Concept/Lazy%20Evaluation)

![](topics/Tool/CSV%20Reader%20Writer)

![](topics/Concept/Data%20Transformation)

![](topics/Concept/Joining%20DataFrames)

![](topics/Concept/Aggregation)

![](topics/Concept/Time%20Series%20Handling)