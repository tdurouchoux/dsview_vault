---
already_read: true
link: https://opensource.posit.co/resources/cheatsheets/polars/
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Python
type: Content
upload_date: '2026-09-10'
---

https://opensource.posit.co/resources/cheatsheets/polars/

## Summary

Polars is a high-performance DataFrame library for Python, offering an expressive API for data transformation, analysis, and visualization.

**Core Features**
- Released in 2020 by Ritchie Vink, built on Apache Arrow memory format.
- Supports eager (immediate) and lazy (optimized query plan) execution modes.
- No row index; favors immutability and method chaining.

**Data Structures**
- `Series`: 1D sequence of same-type values.
- `DataFrame`: 2D structure (columns = Series of equal length).
- `LazyFrame`: Blueprint for deferred DataFrame generation.

**Key Capabilities**
- **Eager/Lazy APIs**: `.lazy()` converts DataFrame to LazyFrame; `.collect()` executes LazyFrame.
- **Optimizations**: Predicate/projection pushdown, streaming for out-of-core processing.
- **Query Inspection**: `.explain()`, `.show_graph()`, `.profile()` for performance analysis.

**Data Types**
- Numeric: `Int8`–`Int128`, `UInt8`–`UInt64`, `Float32/64`, `Decimal`.
- Temporal: `Date`, `Datetime`, `Duration`, `Time`.
- Nested: `Array`, `List`, `Struct`.
- Other: `String`, `Categorical`, `Boolean`, `Binary`, `Null`.

**I/O Operations**
- Supports `read_*`, `scan_*`, `write_*`, `sink_*` for CSV, Parquet, JSON, Delta Lake, etc.
- Cloud storage via URIs (e.g., `s3://bucket/*.parquet`) with `storage_options`.

**Transformations**
- **Selecting**: `select()`, `pl.col()`, regex patterns, column selectors (`cs.numeric()`).
- **Creating Columns**: `with_columns()`, `fill_null()`, `lit()`, `row_index()`.
- **Filtering**: `filter()`, `drop_nulls()`, `unique()`, logical operators (`&`, `|`).
- **Reshaping**: `unpivot()`, `pivot()`, `explode()`, `transpose()`.
- **Aggregations**: `group_by()`, `agg()`, window functions (`over()`), rolling/dynamic groups.

**Joins & Concatenation**
- `join()` (inner/left/right/full), `join_asof()` (time-series), `join_where()` (predicate-based).
- `concat()` (vertical/horizontal/diagonal), `update()`.

**Expressions**
- Arithmetic (`+`, `-`, `*`, `/`), comparisons (`<`, `>`, `==`), boolean logic (`&`, `|`, `~`).
- Conditional: `when().then().otherwise()`.
- Math: `abs()`, `log()`, `sqrt()`, rounding, trigonometry.
- Missing values: `fill_null()`, `is_null()`, `drop_nulls()`.
- Rolling/cumulative: `rolling_mean()`, `cum_sum()`, `shift()`.
- Strings: `str.contains()`, `str.split()`, `str.to_uppercase()`.
- Dates: `dt.month()`, `dt.strftime()`, `dt.convert_time_zone()`.

**Visualization & Styling**
- Built-in plotting via Altair (`df.plot.scatter()`).
- Compatible with Plotnine, Plotly, Seaborn, Matplotlib (convert to pandas with `.to_pandas()`).
- Styling with Great Tables (`GT(df)`).

**Advanced**
- Polars Cloud: Distributed execution via `polars_cloud` (`ComputeContext`, `remote()`).
- Based on the book *Python Polars: The Definitive Guide* (O’Reilly).

## Links

- [Polars Official Website](https://pola.rs) : The official website for Polars, a fast and expressive DataFrame library for Python, providing documentation, installation guides, and community resources.
- [Python Polars: The Definitive Guide](https://polarsguide.com) : The official website for the book 'Python Polars: The Definitive Guide' by Jeroen Janssens and Thijs Nieuwdorp, which serves as the basis for the provided cheatsheet.
- [Great Tables Documentation](https://posit-dev.github.io/great-tables/) : Documentation for Great Tables, a Python library designed to create presentation-ready tables from Polars DataFrames, as referenced in the cheatsheet.


## Topics

![[topics/Library/Great Tables]]

![[topics/Concept/LazyFrame]]

![[topics/Concept/Eager API]]

![[topics/Concept/DataFrame]]

![[topics/Concept/Series]]

![[topics/Library/Polars]]

![[topics/Library/plotnine]]

![[topics/Platform/Polars Cloud]]

![[topics/Library/Apache Arrow]]