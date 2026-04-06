---
type: Concept
---

Dictionary encoding is a technique used in Parquet files to reduce storage space by replacing repeated values with references to a dictionary of unique values. This method is particularly effective for columns with low cardinality (few unique values). Parquet files can dynamically switch between dictionary and plain encoding based on the data distribution and configuration settings, such as `dictionary_page_size_limit`. Proper tuning of dictionary encoding can improve both compression and decoding performance.