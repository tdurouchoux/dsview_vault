---
already_read: false
link: https://github.com/deepseek-ai/smallpond
read_priority: 2
relevance: 0
source: Blef
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2025-03-09'
---

https://github.com/deepseek-ai/smallpond
## Summary

Smallpond is a lightweight data processing framework built on DuckDB and 3FS. Key features include:

- High-performance data processing powered by DuckDB
- Scalability to handle PB-scale datasets
- Easy operations with no long-running services

Installation is straightforward with Python 3.8 to 3.12 support:
```bash
pip install smallpond
```

Quick start example:
```python
import smallpond
sp = smallpond.init()
df = sp.read_parquet("prices.parquet")
df = df.repartition(3, hash_by="ticker")
df = sp.partial_sql("SELECT ticker, min(price), max(price) FROM {0} GROUP BY ticker", df)
df.write_parquet("output/")
print(df.to_pandas())
```

Performance is notable, achieving 3.66TiB/min throughput in the GraySort benchmark. Development and documentation building instructions are provided. The project is licensed under MIT.
## Links

- [smallpond Documentation](https://deepseek-ai.github.io/smallpond/) : The official documentation for smallpond, providing detailed guides and API references for the data processing framework.
- [3FS Repository](https://github.com/deepseek-ai/3FS) : The GitHub repository for 3FS, a distributed file system that complements smallpond's data processing capabilities.
- [DuckDB Website](https://duckdb.org/) : The official website for DuckDB, an in-process SQL OLAP database management system that powers smallpond.

## Topics

![](topics/Library/smallpond)

![](topics/Platform/3FS)