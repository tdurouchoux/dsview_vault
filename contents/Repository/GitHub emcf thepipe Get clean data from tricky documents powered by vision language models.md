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
- **Supported File Types**: Includes webpages, PDFs, Word documents, PowerPoints, videos, audio, Jupyter notebooks, spreadsheets, images, ZIP files, directories, YouTube videos, tweets, and GitHub repositories.

Thepipe uses a combination of computer-vision models and heuristics to process content for downstream use with large language models or vision-language models. It can be installed via pip and configured with environment variables for API keys, hosting, and model defaults. The project welcomes contributions and is licensed under the MIT license.
## Links

- [thepipe](https://thepi.pe) : thepipe is a package that can scrape clean markdown, multimodal media, and structured data from complex documents.
- [OpenAI Structured Outputs](https://platform.openai.com/docs/guides/structured-outputs?api-mode=chat) : OpenAI's documentation on structured outputs, which is recommended for structured data extraction.
- [OpenLLM](https://github.com/bentoml/OpenLLM) : OpenLLM is a project that provides a way to run local vision-language models, which can be used with thepipe.
- [Sentence Transformers](https://pypi.org/project/sentence-transformers/) : Sentence Transformers is a Python library for state-of-the-art sentence, text, and image embeddings.
- [Trellis AI](https://runtrellis.com/) : Trellis AI is a platform for automated workflows with structured data, which is recommended by thepipe for enterprise-ready document processing and intelligent automation.

## Topics

![](topics/Library/thepipe)

![](topics/Concept/Vision%20Language%20Models)

![](topics/Concept/Retrieval%20Augmented%20Generation)