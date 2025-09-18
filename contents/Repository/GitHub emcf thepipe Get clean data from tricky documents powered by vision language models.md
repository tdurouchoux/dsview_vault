---
already_read: true
link: https://github.com/emcf/thepipe
read_priority: 0
relevance: 0
source: Data Elixir
tags:
- Natural_Language_Processing
- Computer_Vision
type: Content
upload_date: '2024-09-24'
---

https://github.com/emcf/thepipe
## Summary

Thepipe is a Python package designed to extract clean data from complex documents using vision-language models (VLMs). It supports a wide range of file types, including PDFs, URLs, Word docs, Powerpoints, videos, audio, and more. Key features include:

- **Scraping**: Extracts clean markdown, tables, images, and other media from documents.
- **Chunking**: Splits content into smaller chunks to satisfy token-limit constraints, with methods like `chunk_by_page`, `chunk_by_section`, and experimental methods like `chunk_semantic` and `chunk_agentic`.
- **Integration**: Works out-of-the-box with OpenAI, LlamaIndex, and other RAG frameworks.
- **Structured Extraction**: Deprecated in favor of OpenAI's structured outputs or Trellis AI for automated workflows.
- **CLI Usage**: Provides command-line options for scraping and configuration.

Thepipe uses computer-vision models and heuristics to process content for downstream use with large language models or vision-language models. It supports various file types and can be configured via environment variables for API keys, hosting, and model defaults. Contributions are welcome, and the project is licensed under MIT.
## Links

- [Thepipe API Download](https://www.pepy.tech/projects/thepipe-api) : Thepipe API download statistics and information.
- [Sentence Transformers](https://pypi.org/project/sentence-transformers/) : Sentence Transformers is a Python framework for state-of-the-art sentence, text, and image embeddings, which can be used for semantic search, clustering, and more.
- [OpenLLM](https://github.com/bentoml/OpenLLM) : OpenLLM is a project that provides a collection of large language models that can be run locally or in the cloud.

## Topics

![[topics/Concept/Retrieval Augmented Generation RAG]]

![[topics/Library/thepipe]]

![[topics/Concept/Text Chunking]]

![[topics/Concept/Vision Language Models]]