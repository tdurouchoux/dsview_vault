---
already_read: false
link: https://minimaxir.com/2025/02/embeddings-parquet/
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Natural_Language_Processing
- Data_Analysis
- Development_tool
type: Content
upload_date: '2025-02-25'
---

https://minimaxir.com/2025/02/embeddings-parquet/
## Summary

- **Text Embeddings**: Text embeddings are numerical representations of text data, useful for tasks like similarity search and clustering. They can represent words, sentences, or entire documents.

- **Use Case**: The author generated embeddings for Magic: the Gathering cards using the gte-modernbert-base model. These embeddings were used to find similar cards and create a 2D UMAP projection, revealing patterns like card colors and types.

- **Storing Embeddings**: Common methods include CSV, text files, and Python pickles. However, these methods have drawbacks such as large file sizes, security risks, and lack of metadata handling.

- **Parquet Files**: Parquet is a columnar file format that efficiently stores typed data, including nested lists like embeddings. It supports compression and selective loading, making it suitable for embeddings.

- **Polars Library**: Polars is a high-performance DataFrame library that supports Arrow and Parquet. It handles nested data efficiently and provides zero-copy conversion to numpy arrays, making it ideal for embeddings.

- **Filtering and Similarity Search**: Using Parquet and Polars, you can filter embeddings based on metadata and perform similarity searches efficiently. The author provides an example using Magic card data.

- **Scaling**: For larger datasets, vector databases like faiss or qdrant may be more suitable. However, Parquet and Polars can still be used for smaller projects or when portability is a priority.

- **Conclusion**: For many applications, Parquet files and Polars offer an efficient and portable solution for storing and working with text embeddings, eliminating the need for a vector database in some cases.
## Links

- [Numpy load](https://numpy.org/doc/2.1/reference/generated/numpy.load.html) : Numpy load documentation
- [SQLite](https://www.sqlite.org) : SQLite official website
- [Magic: The Gathering](https://magic.wizards.com/en) : Magic: The Gathering official website
- [Pinecone](https://www.pinecone.io) : Pinecone official website
- [gRPC](https://grpc.io) : gRPC official website
- [gte-modernbert-base](https://huggingface.co/Alibaba-NLP/gte-modernbert-base) : gte-modernbert-base model on Hugging Face
- [Numpy strings](https://numpy.org/devdocs/user/basics.strings.html) : Numpy strings documentation
- [Apache Arrow](https://arrow.apache.org) : Apache Arrow official website
- [Numpy](https://numpy.org/doc/stable/index.html) : Numpy official documentation
- [mtg-embeddings](https://github.com/minimaxir/mtg-embeddings) : mtg-embeddings GitHub repository
- [UMAP](https://umap-learn.readthedocs.io/en/latest/) : UMAP documentation
- [Numpy vstack](https://numpy.org/doc/2.1/reference/generated/numpy.vstack.html) : Numpy vstack documentation
- [Qdrant](https://github.com/qdrant/qdrant?tab=readme-ov-file#client-server) : Qdrant GitHub repository
- [Faiss](https://github.com/facebookresearch/faiss/wiki/Guidelines-to-choose-an-index) : Faiss GitHub repository
- [Parquet](https://blog.x.com/engineering/en_us/a/2013/announcing-parquet-10-columnar-storage-for-hadoop) : Parquet announcement blog post
- [Pinecone Python SDK](https://docs.pinecone.io/reference/python-sdk) : Pinecone Python SDK documentation
- [Wrath of God card](https://gatherer.wizards.com/pages/card/details.aspx?multiverseid=87908) : Wrath of God card details on Gatherer
- [Numpy argpartition](https://numpy.org/doc/stable/reference/generated/numpy.argpartition.html) : Numpy argpartition documentation
- [Numpy savetxt](https://numpy.org/doc/stable/reference/generated/numpy.savetxt.html) : Numpy savetxt documentation
- [Text embeddings introduction](https://stackoverflow.blog/2023/11/09/an-intuitive-introduction-to-text-embeddings/) : Introduction to text embeddings blog post
- [Write better code](https://minimaxir.com/2025/01/write-better-code/) : Write better code blog post
- [DuckDB benchmark](https://duckdblabs.github.io/db-benchmark/) : DuckDB benchmark website
- [Numpy loadtxt](https://numpy.org/doc/stable/reference/generated/numpy.loadtxt.html) : Numpy loadtxt documentation
- [Patreon](https://www.patreon.com/minimaxir) : Max Woolf's Patreon page
- [Polars documentation](https://docs.pola.rs/#key-features) : Polars documentation
- [YouTube](https://youtube.com/minimaxir) : Max Woolf's YouTube channel
- [Python pickle](https://docs.python.org/3/library/pickle.html) : Python pickle documentation
- [Apache Arrow Python](https://arrow.apache.org/docs/python/index.html) : Apache Arrow Python documentation
- [Scikit-learn](https://scikit-learn.org/stable/) : Scikit-learn official website
- [Polars Series to_numpy](https://docs.pola.rs/api/python/stable/reference/series/api/polars.Series.to_numpy.html) : Polars Series to_numpy documentation
- [mtg-embeddings dataset](https://huggingface.co/datasets/minimaxir/mtg-embeddings) : mtg-embeddings dataset on Hugging Face
- [Colab Notebook](https://colab.research.google.com/drive/19C_9sBC0Py2PlXYihl2ed378oGyroONZ?usp=sharing) : Interactive Colab Notebook for Magic card embeddings
- [Pinecone pricing](https://www.pinecone.io/pricing/) : Pinecone pricing page
- [Numpy save](https://numpy.org/doc/2.1/reference/generated/numpy.save.html) : Numpy save documentation
- [OpenAI cookbook](https://github.com/openai/openai-cookbook/blob/main/examples/Question_answering_using_embeddings.ipynb) : OpenAI cookbook GitHub repository
- [Pandas](https://pandas.pydata.org) : Pandas official website
- [Parquet](https://parquet.apache.org) : Parquet official website
- [LLM use](https://minimaxir.com/2025/05/llm-use/) : LLM use blog post
- [Rust](https://www.rust-lang.org) : Rust official website
- [Vector database](https://en.wikipedia.org/wiki/Vector_database) : Vector database Wikipedia page
- [Polars](https://pola.rs) : Polars official website
- [Numpy argsort](https://numpy.org/doc/2.1/reference/generated/numpy.argsort.html) : Numpy argsort documentation
- [OpenAI embeddings](https://platform.openai.com/docs/guides/embeddings) : OpenAI embeddings documentation
- [Lightning Helix card](https://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=464058) : Lightning Helix card details on Gatherer
- [BuzzFeed](https://www.buzzfeed.com) : BuzzFeed official website
- [Twitch](https://twitch.tv/minimaxir) : Max Woolf's Twitch channel
- [Numpy](https://numpy.org/doc/stable/index.html) : Numpy official documentation
- [Max Woolf's blog](https://minimaxir.com/post/) : Max Woolf's blog
- [Hugo](https://gohugo.io/) : Hugo static site generator website

## Topics

![](topics/Model/gte%20modernbert%20base)

![](topics/Dataset/Magic%20the%20Gathering%20Card%20Dataset)

![](topics/Concept/UMAP%20Uniform%20Manifold%20Approximation%20and%20Projection)

![](topics/Tool/Apache%20Parquet)

![](topics/Tool/sqlite%20vec)

![](topics/Library/Polars)