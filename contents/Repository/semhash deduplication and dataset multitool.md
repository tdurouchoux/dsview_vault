---
already_read: true
link: https://minishlab.github.io/semhash-blogpost/
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Large_Language_Model
- Data_Quality
type: Content
upload_date: '2025-01-22'
---

https://minishlab.github.io/semhash-blogpost/
## Summary

- **semhash**: A fast semantic deduplication and dataset multitool for high-quality data processing.
- **Key Features**:
  - Removes semantically similar documents, improving data quality for LLM training and other tasks.
  - Uses a fast model (potion-base-8m) for efficient deduplication.
  - Supports multi-column datasets, allowing deduplication based on multiple text fields.
- **Use Cases**:
  - Ensuring no overlap between train and test splits in classification tasks.
  - Removing duplicate chunks in RAG systems to improve efficiency and relevance.
  - Exploring and understanding the structure of large datasets.
- **How It Works**:
  - Encodes documents using a model2vec encoder (default: potion-base-8m).
  - Stores encoded documents in a vicinity vector store backed by usearch.
  - Retrieves nearest neighbors for incoming documents and removes duplicates based on a similarity threshold.
- **Performance**:
  - Deduplicates large datasets (e.g., Squad-2.0 with 130,000 samples) in seconds to minutes.
- **Explainability**:
  - Provides insights into duplicate records, including exact and approximate duplicates.
  - Allows adjustment of the similarity threshold to fine-tune deduplication results.
- **Availability**: semhash is available for use, with a call to action to try it out.
## Links

- [semhash GitHub Repository](https://github.com/MinishLab/semhash) : The GitHub repository for semhash, a semantic deduplication and dataset multitool.
- [semhash Benchmarks](https://github.com/MinishLab/semhash?tab=readme-ov-file#benchmarks) : Benchmarks for semhash, demonstrating its performance on various datasets.
- [potion-base-8M Model](https://huggingface.co/minishlab/potion-base-8M) : The potion-base-8M model, used as the default encoder in semhash.

## Topics

![](topics/Tool/semhash)