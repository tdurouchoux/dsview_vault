---
already_read: false
link: https://minimaxir.com/2025/02/embeddings-parquet/
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2025-02-25'
---

https://minimaxir.com/2025/02/embeddings-parquet/
## Summary

Text embeddings, particularly those created from large language models, serve as valuable representations of text objects like words and sentences. The author created embeddings for over 32,000 Magic: The Gathering cards to analyze similarity across their mechanics. Traditional solutions for storing and querying these embeddings, such as vector databases, can be complex and costly.

Instead, the author suggests using Parquet files combined with the Polars library for efficient storage and manipulation of embeddings. Key advantages of Parquet include lower file size compared to text formats like CSV and the ability to manage both metadata and numerical data (embeddings). 

The article warns against common pitfalls like saving embeddings in text formats or using pickles, which can hinder portability and introduce security risks. Instead, it highlights the use of NumPy for straightforward embedding operations, and the benefits of Polars for handling nested data efficiently and with better performance than pandas.

Polars allows easy integration with Parquet files and provides functionality to filter datasets while maintaining low computational overhead. The proposed approach is efficient for smaller projects but notes that larger applications may still benefit from vector databases or even SQLite with extensions for vector embeddings.

Overall, combining Parquet and Polars is presented as a practical solution for managing text embeddings in a flexible and performant way, enabling easy experimentation and portability.
## Links

- [Hugging Face Dataset for MTG Embeddings](https://huggingface.co/datasets/minimaxir/mtg-embeddings) : Dataset of embeddings for Magic: the Gathering cards, useful for working with text embeddings.
- [PyArrow Documentation](https://arrow.apache.org/docs/python/index.html) : Documentation for PyArrow, the library that allows the use of Parquet files in Python.
- [Polars Documentation](https://docs.pola.rs/#key-features) : Documentation for Polars, a high-performance DataFrame library that supports Arrow and is suitable for handling nested data.
- [Faiss GitHub Repository](https://github.com/facebookresearch/faiss) : Faiss is a library for efficient similarity search and clustering of dense vectors.
- [Pandas Documentation for Read Parquet](https://pandas.pydata.org/docs/reference/api/pandas.read_parquet.html) : Pandas function to read Parquet files, relevant for handling embeddings.

## Topics

![](topics/Concept/Text%20Embeddings)

![](topics/Library/Polars)

![](topics/Library/PyArrow)

![](topics/Tool/Parquet)

![](topics/Library/NumPy)

![](topics/Library/Faiss)

![](topics/Library/Qdrant)

![](topics/Library/Hugging%20Face%20Datasets)

![](topics/Concept/Cosine%20Similarity)

![](topics/Tool/SQLite)