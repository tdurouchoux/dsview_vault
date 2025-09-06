---
already_read: true
link: https://github.com/dleemiller/WordLlama
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Natural_Language_Processing
- Large_Language_Model
type: Content
upload_date: '2024-10-02'
---

https://github.com/dleemiller/WordLlama
## Summary

WordLlama is a lightweight NLP toolkit designed for tasks like fuzzy deduplication, similarity computation, ranking, clustering, and semantic text splitting. It operates with minimal dependencies and is optimized for CPU hardware, making it suitable for resource-constrained environments.

Key features include:
- Fast embeddings using token lookup with average pooling
- Similarity computation and ranking of documents
- Fuzzy deduplication and clustering
- Semantic text splitting
- Binary embeddings for faster computations
- Matryoshka representations for flexible dimension truncation

WordLlama recycles components from large language models (LLMs) to create efficient and compact word representations. It starts by extracting the token embedding codebook from state-of-the-art LLMs (e.g., LLaMA 2, LLaMA 3 70B) and trains a small context-less model within a general-purpose embedding framework. This results in a lightweight model that improves on MTEB benchmarks over traditional word models like GloVe 300d, while being substantially smaller in size (e.g., 16MB default model at 256 dimensions).

The toolkit includes various usage examples, such as embedding text, calculating similarity, ranking documents, fuzzy deduplication, clustering, filtering, top-K retrieval, and semantic text splitting. It also supports loading Model2Vec for static embeddings and provides an inference class for custom embeddings.

WordLlama is licensed under the MIT License and includes a citation for academic or project use. The repository also features community projects and a roadmap for additional example notebooks, such as DSPy evaluators and RAG pipelines.
## Links

- [WordLlama Hugging Face Space](https://huggingface.co/spaces/1littlecoder/wordllama) : Gradio Demo for WordLlama on Hugging Face Spaces.
- [Model2Vec](https://github.com/MinishLab/model2vec) : Model2Vec is a different way of creating static embeddings using PCA.
- [CPU-ish RAG](https://github.com/dinhanhx/cpu-ish-rag) : Community project related to WordLlama.

## Topics

![](topics/Library/WordLlama)

![](topics/Concept/Matryoshka%20Representations)

![](topics/Concept/Binary%20Embeddings)

![](topics/Concept/Semantic%20Text%20Splitting)

![](topics/Concept/Model2Vec)