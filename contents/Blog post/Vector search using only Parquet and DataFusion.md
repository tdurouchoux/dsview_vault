---
already_read: true
link: https://blog.xiangpeng.systems/posts/vector-search-with-parquet-datafusion/
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2026-03-31'
---

https://blog.xiangpeng.systems/posts/vector-search-with-parquet-datafusion/
## Summary

The post explores implementing efficient vector search directly in Parquet files using the `pq-vector` library, avoiding traditional vector databases.

Key technical points:
- **Random Access Optimization**: Configure Parquet's page size to match embedding dimensions (e.g., 6KB) to enable efficient single-vector retrieval without full decompression.
- **Zero-Copy Indexing**: Embed an IVF (Inverted File) index in Parquet's metadata footer, referencing vectors without duplication. Overhead is minimal (~0.3% for 5K vectors).
- **In-Place Index Creation**: Append the index to the footer without rewriting data pages, leveraging Parquet's metadata flexibility.
- **DataFusion Integration**: Extend DataFusion's query optimizer to auto-rewrite plans for indexed vector search using standard SQL (e.g., `ORDER BY array_distance(...)`).
- **Performance**: Achieves 5.7x speedup with 96% recall (nprobe=5) vs. brute-force scans (100ms → 17.7ms).
- **Limitations**: Early-stage prototype; plans include HNSW support, multi-Parquet indexing, and improved filter integration.

Tools/Libraries: Parquet, DataFusion, Rust (`pq-vector` GitHub repo).
## Links

- [DataFusion User-Defined Parquet Indexes](https://datafusion.apache.org/blog/2025/07/14/user-defined-parquet-indexes/) : A blog post explaining how to implement user-defined indexes for Parquet files in DataFusion, demonstrating its extensibility for custom indexing solutions.
- [LanceDB Documentation](https://lancedb.com/) : Official documentation for LanceDB, a vector database designed for efficient vector search, providing a comparison point for the Parquet-based approach discussed in the blog post.
- [Pinecone Vector Indexes Guide](https://www.pinecone.io/learn/series/faiss/vector-indexes/) : Educational content from Pinecone on vector indexes using FAISS, highlighting traditional vector database approaches and their trade-offs compared to the Parquet-based method.
- [Apache Parquet WriterProperties Documentation](https://docs.rs/parquet/latest/parquet/file/properties/struct.WriterPropertiesBuilder.html) : Documentation for Parquet's WriterPropertiesBuilder, which is used to configure Parquet files for optimal random access, a key technique in enabling efficient vector search.
- [Milvus Vector Database](https://milvus.io/) : Official website for Milvus, an open-source vector database, providing context for alternative solutions discussed in the blog post.

## Topics

![[topics/Library/DataFusion]]

![[topics/Library/pq vector]]

![[topics/Concept/Zero copy Vector Indexing]]

![[topics/Concept/Inverted File IVF Index]]

![[topics/Concept/Parquet Page Size Tuning]]

![[topics/Concept/In Place Index Creation]]