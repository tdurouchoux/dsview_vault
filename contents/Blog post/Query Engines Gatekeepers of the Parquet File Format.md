---
already_read: false
link: https://duckdb.org/2025/01/22/parquet-encodings
read_priority: 4
relevance: 0
source: Blef
tags:
- Data_Engineering
- Data_Analysis
type: Content
upload_date: '2025-03-09'
---

https://duckdb.org/2025/01/22/parquet-encodings
## Summary

The article discusses the Parquet file format, its advantages, and the challenges faced by query engines like DuckDB in supporting newer Parquet encodings. Key points include:

1. **Parquet Format**: Column-oriented, efficient for querying, and widely used for data interchange.
2. **Backward Compatibility**: Important for both DuckDB and Parquet to maintain the ability to read older file formats.
3. **New Encodings**: DuckDB supports newer Parquet encodings (DELTA_BINARY_PACKED, DELTA_LENGTH_BYTE_ARRAY, BYTE_STREAM_SPLIT) but does not write them by default due to lack of support in mainstream query engines.
4. **Compression Benefits**: Newer encodings offer better compression ratios and faster write times, but their use is limited by query engine support.
5. **Wasted Bits**: Lack of support for newer encodings leads to inefficient storage, wasting significant amounts of data center space.
6. **Call to Action**: The article urges mainstream query engines to implement support for newer Parquet encodings to improve efficiency and reduce data storage waste.

The article concludes by emphasizing the shared responsibility of query engine developers to enhance Parquet's usefulness and efficiency.
## Links

- [Parquet Format Encodings](https://parquet.apache.org/docs/file-format/data-pages/encodings/) : Apache Parquet documentation on data encodings, detailing various encoding methods used in Parquet files.
- [Parquet Format Changes](https://github.com/apache/parquet-format/blob/master/CHANGES.md) : GitHub repository for Parquet format changes, tracking updates and modifications to the Parquet file format.

## Topics

![](topics/Tool/Apache%20Parquet)

![](topics/Library/DuckDB)