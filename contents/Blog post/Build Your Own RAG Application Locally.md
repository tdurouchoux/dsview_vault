---
already_read: false
link: https://blog.duy-huynh.com/build-your-own-rag-and-run-them-locally/
read_priority: 1
source: null
tags:
- Large_Language_Model
- Natural_Language_Processing
- Python
type: Content
upload_date: '2024-01-11'
---

https://blog.duy-huynh.com/build-your-own-rag-and-run-them-locally/
## Summary

The article discusses building a Retrieval Augmented Generation (RAG) application locally using Langchain, Ollama, and Streamlit. It emphasizes the importance of RAG in enhancing the capabilities of Large Language Models (LLMs) by retrieving accurate information to support user queries.

Key components of the application include:
- **LLM Server**: Ollama is recommended for its ease of setup on local machines.
- **RAG Framework**: Langchain is used for its familiarity and integration with vector storage, specifically Chroma.
- **User Interface**: Streamlit is chosen for its simplicity in creating a user-friendly interface.

The setup process involves:
1. Installing Ollama and pulling the Mistral-7B model.
2. Building the RAG pipeline with methods for ingesting documents and handling user queries.
3. Utilizing PyPDFLoader and RecursiveCharacterSplitter to process PDF files and store them in vector format.

The article also suggests enhancements such as adding memory to the conversation chain, allowing multiple file uploads, experimenting with different LLM models, and improving the RAG pipeline.

Overall, the guide provides a high-level overview of creating a local RAG application, encouraging further exploration and development.
## Links

1. [Langchain Documentation](https://python.langchain.com/docs/get_started/introduction) - Official documentation for Langchain, a library for building applications with LLMs.
2. [Ollama](https://ollama.ai/) - A platform for running LLMs locally, which is a key component in the discussed RAG application.
3. [Chroma](https://github.com/chroma-core/chroma) - GitHub repository for Chroma, a vector storage solution used in the RAG pipeline.
4. [Qdrant FastEmbed](https://github.com/qdrant/fastembed/) - GitHub repository for FastEmbed, an embedding model used for vectorization in the RAG application.
5. [Retrieval Augmented Generation (RAG) Guide](https://www.datastax.com/guides/what-is-retrieval-augmented-generation) - A comprehensive guide explaining RAG, its use cases, and how it integrates with vector databases.
## Topics

![](topics/Library/Langchain)

![](topics/Library/Ollama)

![](topics/Platform/Streamlit)

![](topics/Library/Chroma)

![](topics/Model/Mistral%207B)