---
already_read: false
link: https://minimaxir.com/2025/02/embeddings-parquet/
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Data_Analysis
- Development_tool
type: Content
upload_date: '2025-02-25'
---

https://minimaxir.com/2025/02/embeddings-parquet/
## Summary

- **Text Embeddings**: Represent text data as numerical vectors, useful for finding similarities between texts.
- **Use Case**: Max Woolf generated embeddings for Magic: the Gathering cards, enabling similarity searches and visualizations.
- **Challenges with Vector Databases**: Tools like faiss, qdrant, and Pinecone have limitations in terms of usability, cost, and portability.
- **Alternative Approach**: Using Parquet files and Polars for storing and manipulating embeddings.
  - **Parquet Files**: Efficient for storing embeddings and metadata together, supporting fast I/O and compression.
  - **Polars**: A high-performance DataFrame library that handles nested data efficiently, interoperates well with numpy, and supports zero-copy operations.
- **Implementation**:
  - Store embeddings and metadata in Parquet files.
  - Use Polars for fast and efficient data manipulation, including filtering and similarity searches.
  - Perform dot product calculations for similarity searches using numpy.
- **Performance**: The approach is efficient for smaller datasets and hobby projects, with Polars offering significant speed advantages over pandas.
- **Scaling**: For larger datasets, consider vector databases or SQLite with vector extensions.
- **Code and Data**: Available on GitHub for generating embeddings and performing similarity searches.

Key takeaways:
- Parquet files and Polars provide a portable and efficient way to handle text embeddings.
- Polars offers better performance and support for nested data compared to pandas.
- The approach is suitable for smaller projects, with options to scale using vector databases or SQLite extensions for larger datasets.
## Links

- [Apache Parquet](https://parquet.apache.org) : Apache Parquet is a columnar storage file format optimized for use with big data processing frameworks.
- [Polars](https://pola.rs) : Polars is a high-performance DataFrame library implemented in Rust, designed for efficient data manipulation and analysis.
- [Numpy](https://numpy.org/doc/stable/index.html) : NumPy is a fundamental package for scientific computing with Python, providing support for arrays, matrices, and many mathematical functions to operate on these data structures.

## Topics

![[topics/Library/polars)]]

![[topics/Concept/UMAP)]]

![[topics/Library/Apache Arrow)]]

![[topics/Concept/Parquet)]]

![[topics/Dataset/Magic the Gathering Card Dataset)]]

![[topics/Model/gte modernbert base)]]