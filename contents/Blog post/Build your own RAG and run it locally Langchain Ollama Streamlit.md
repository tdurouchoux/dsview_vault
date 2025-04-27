---
already_read: false
link: https://blog.duy-huynh.com/build-your-own-rag-and-run-them-locally/
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2024-01-11'
---

https://blog.duy-huynh.com/build-your-own-rag-and-run-them-locally/
## Summary

The guide outlines how to create a Retrieval-Augmented Generation (RAG) application locally using Langchain, Ollama, and Streamlit. It highlights the rise of Large Language Models (LLMs) and explains the architecture of the application, focusing on:

1. **LLM Server**: Ollama serves as the local LLM server, which can be set up easily. The example uses the Mistral-7B model for its size and performance.
  
2. **RAG Pipeline**: The application comprises two primary methods—ingest (for loading and vectorizing PDF documents into storage) and ask (for querying). It uses PyPDFLoader to process documents and Chroma for vector storage, utilizing Qdrant FastEmbeddings for vectorization.

3. **User Interface**: Streamlit is employed for creating a user-friendly interface that allows users to upload PDFs and ask questions.

Suggestions for further enhancements include adding memory to the conversation chain, enabling multiple file uploads, experimenting with different LLM models, and refining the RAG pipeline for better retrieval accuracy. The source code is provided for reference.
## Links

- [Comprehensive Guide for Building RAG-based LLM Applications](https://www.anyscale.com/blog/a-comprehensive-guide-for-building-rag-based-llm-applications-part-1?ref=blog.duy.dev) : A detailed guide on developing and productionizing RAG-based LLM applications with a focus on scale and evaluation.
- [What is Retrieval-Augmented Generation?](https://www.datastax.com/guides/what-is-retrieval-augmented-generation?ref=blog.duy.dev) : An overview of RAG, explaining its use cases and how vector search and databases play a role in its function.
- [Retrieval-augmented generation: An overview by IBM](https://research.ibm.com/blog/retrieval-augmented-generation-RAG?ref=blog.duy.dev) : A blog post from IBM Research discussing the RAG framework for enhancing LLMs with accurate information retrieval.
- [Langchain Documentation](https://python.langchain.com/docs/get_started/introduction?ref=blog.duy.dev) : Official documentation for Langchain, a library designed for building applications powered by LLMs.
- [Chroma GitHub Repository](https://github.com/chroma-core/chroma?ref=blog.duy.dev) : The GitHub repository for Chroma, a storage library used for vector storage in RAG implementations.

## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Library/Langchain)

![](topics/Library/Chroma)

![](topics/Tool/Streamlit)

![](topics/Model/Mistral%207B)