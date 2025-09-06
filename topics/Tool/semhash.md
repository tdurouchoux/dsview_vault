---
type: Tool
---

Semhash is a semantic deduplication and dataset multitool designed for fast and efficient deduplication of text data. It uses semantic similarity to identify and remove duplicate documents, making it useful for improving data quality in various applications such as training Large Language Models (LLMs), classification tasks, and RAG systems. Semhash operates by encoding documents using a model2vec encoder and storing them in a vicinity vector store backed by usearch. It then retrieves nearest neighbors for incoming documents and removes those that are semantically similar above a specified threshold. The tool is highly efficient, capable of deduplicating large datasets in minutes, and offers features for explainability and multi-column data support.