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

The article discusses the role of query engines in supporting the Parquet file format, highlighting that mainstream engines often lag in adopting newer Parquet encodings, which forces systems like DuckDB to default to older, less efficient encodings. Key points include:

1. **Parquet Format**: Parquet is a column-oriented data storage format designed for efficient querying, offering better compression and selective column reading compared to formats like CSV or JSON.

2. **Backward Compatibility**: Maintaining backward compatibility is crucial for both DuckDB and Parquet. Query engines should be able to read older Parquet files while gradually adopting support for newer encodings.

3. **Encodings**: DuckDB has implemented newer Parquet encodings (DELTA_BINARY_PACKED, DELTA_LENGTH_BYTE_ARRAY, and BYTE_STREAM_SPLIT) but does not use them by default due to lack of support in mainstream query engines. These encodings can significantly improve compression ratios and writing speeds.

4. **Performance Gains**: Using newer encodings can reduce file sizes and writing times, with examples showing improvements ranging from 11% to 99% in compression and up to 31% in writing speed.

5. **Wasted Bits**: The lack of support for newer encodings results in wasted storage space. Implementing these encodings can reduce data storage needs and potentially decrease the need for new data centers.

6. **Conclusion**: The article emphasizes the shared responsibility of query engine developers to implement newer Parquet encodings to make the format more efficient and reduce wasted storage.
## Links

- [Parquet Format Changelog](https://github.com/apache/parquet-format/blob/master/CHANGES.md) : The changelog for the Apache Parquet format, detailing updates and changes to the format over time.
- [Parquet Encodings Documentation](https://parquet.apache.org/docs/file-format/data-pages/encodings/) : Documentation on Parquet encodings, explaining the different encodings available in the Parquet file format.

## Topics

![](topics/Concept/Apache%20Parquet)

![](topics/Concept/Backward%20Compatibility)

![](topics/Concept/Data%20Compression)

![](topics/Concept/Query%20Engines)

![](topics/Library/DuckDB)