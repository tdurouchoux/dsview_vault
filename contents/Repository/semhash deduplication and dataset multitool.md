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

- **Introduction**: semhash is a tool for semantic deduplication and dataset management, designed to improve data quality for tasks like training Large Language Models (LLMs). It focuses on removing semantically similar documents, addressing limitations of traditional methods like minhash or simhash.

- **Use Cases**:
  - **Classification**: Ensures no overlap between train and test splits, preventing performance overestimation and wasted compute.
  - **RAG Systems**: Identifies duplicate chunks in documents, reducing storage costs and retrieval of irrelevant chunks.
  - **Corpus Analysis**: Provides a quick overview of document similarities within a dataset.

- **How It Works**:
  - Uses an encoder (default: potion-base-8m) to encode documents.
  - Stores encoded documents in a vicinity vector store backed by usearch.
  - Retrieves nearest neighbors for incoming documents and removes those with similarity above a threshold.
  - Processes large datasets quickly (e.g., Squad-2.0 dataset in 7 seconds).

- **Explainability**:
  - Provides deduplicated records, duplicate ratios, and reasons for duplication.
  - Allows adjustment of thresholds to refine deduplication results.
  - Supports multi-column datasets, ensuring similarity across multiple text fields.

- **Conclusion**: semhash is a versatile tool for efficient and effective dataset deduplication and analysis.
## Links

- [semhash GitHub Repository](https://github.com/MinishLab/semhash) : The GitHub repository for semhash, a semantic deduplication and dataset multitool.
- [potion-base-8M Model](https://huggingface.co/minishlab/potion-base-8M) : The potion-base-8M model, a fast model used by semhash for encoding documents.
- [Squad V2 Dataset](https://huggingface.co/datasets/rajpurkar/squad_v2) : The Squad V2 dataset, used as an example in the semhash blogpost.

## Topics

![](topics/Tool/semhash)

![](topics/Model/potion%20base%208m)

![](topics/Concept/Fuzzy%20Deduplication)

![](topics/Concept/Vicinity%20Vector%20Store)