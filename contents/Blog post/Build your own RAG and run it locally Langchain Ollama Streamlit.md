---
already_read: false
link: https://blog.duy-huynh.com/build-your-own-rag-and-run-them-locally/
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- Development_tool
type: Content
upload_date: '2024-01-11'
---

https://blog.duy-huynh.com/build-your-own-rag-and-run-them-locally/
## Summary

This guide provides a step-by-step process to build and run a Retrieval Augmented Generation (RAG) application locally using Langchain, Ollama, and Streamlit. The application allows users to upload a PDF document and ask questions about its content through a simple UI.

**Key Components and Steps:**

1. **LLM Server (Ollama):** The guide uses Ollama to set up a local LLM server with the Mistral-7B model due to its ease of setup and competitive quality.

2. **RAG Pipeline (Langchain):** The RAG pipeline is built using Langchain, with Chroma for vector storage and Qdrant FastEmbeddings for vectorization. The pipeline consists of two main methods:
   - `ingest`: Loads and processes a PDF document into vector storage.
   - `ask`: Handles user queries, retrieves relevant contexts, and generates responses using the LLM server.

3. **Chat UI (Streamlit):** A simple user interface is created using Streamlit for users to interact with the RAG application.

**Suggestions for Enhancement:**
- Add memory to the conversation chain for better context awareness.
- Allow multiple file uploads for chatting about multiple documents.
- Experiment with other LLM models and enhance the RAG pipeline for improved results.

The guide concludes with a link to the full source code on GitHub and encourages readers to subscribe for more content on RAG and LLM applications.
## Links

- [Build your own RAG and run it locally: Langchain + Ollama + Streamlit](https://blog.duy.dev/) : This is the main page of the blog post, providing an overview of building and running a RAG application locally using Langchain, Ollama, and Streamlit.
- [Retrieval Augmented Generation (RAG): A Comprehensive Guide](https://www.datastax.com/guides/what-is-retrieval-augmented-generation?ref=blog.duy.dev) : This guide explains what Retrieval Augmented Generation (RAG) is, specific use cases, and how vector search and vector databases help.
- [What is retrieval-augmented generation? | IBM Research Blog](https://research.ibm.com/blog/retrieval-augmented-generation-RAG?ref=blog.duy.dev) : This article discusses RAG as an AI framework for retrieving facts to ground LLMs on the most accurate information and to give users insight into AI’s decision-making process.
- [Full source code](https://github.com/vndee/local-rag-example?ref=blog.duy.dev) : This is the GitHub repository containing the full source code for building and running a RAG application locally using Langchain, Ollama, and Streamlit.

## Topics

![](topics/Library/LangChain)

![](topics/Model/Mistral%207B)

![](topics/Concept/Vector%20Storage)

![](topics/Library/Streamlit)

![](topics/Concept/Ollama)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Prompt%20Engineering)