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

This guide provides a step-by-step process to build and run a Retrieval Augmented Generation (RAG) application locally using Langchain, Ollama, and Streamlit. The application allows users to upload a PDF document and ask questions about it through a simple UI.

**Key Components and Steps:**

1. **LLM Server (Ollama):** The guide uses Ollama to set up a local LLM server with the Mistral-7B model due to its compact size and competitive quality. The server can be started with the command `ollama serve`.

2. **RAG Pipeline (Langchain):** The RAG pipeline is built using Langchain, with Chroma as the vector storage. The pipeline consists of two main methods:
   - `ingest`: Loads a PDF file, splits it into smaller chunks, vectorizes the chunks using Qdrant FastEmbeddings, and stores them in Chroma.
   - `ask`: Handles user queries by retrieving relevant document chunks using vector similarity search and generating responses using the LLM server.

3. **Chat UI (Streamlit):** A simple user interface is created using Streamlit to allow users to upload PDF files and ask questions.

**Suggestions for Enhancement:**
- Add memory to the conversation chain for better context awareness.
- Allow multiple file uploads for chatting about multiple documents.
- Experiment with other LLM models and enhance the RAG pipeline for improved results.

The full source code for the project is available on GitHub. The guide also provides resources for learning more about RAG and LLM applications.
## Links

- [Langchain Documentation](https://python.langchain.com/docs/get_started/introduction?ref=blog.duy.dev) : Langchain documentation, a library used for building the RAG pipeline.
- [Streamlit Documentation](https://streamlit.io/?ref=blog.duy.dev) : Streamlit documentation, a library used for building the UI.
- [Ollama Documentation](https://ollama.ai/?ref=blog.duy.dev) : Ollama documentation, a library used for running the LLM server.
- [Chroma Documentation](https://github.com/chroma-core/chroma?ref=blog.duy.dev) : Chroma documentation, a library used for vector storage.
- [FastEmbed Documentation](https://github.com/qdrant/fastembed/?ref=blog.duy.dev) : FastEmbed documentation, a library used for vectorizing the document chunks.

## Topics

![[topics/Concept/Retrieval Augmented Generation RAG)]]

![[topics/Library/LangChain)]]

![[topics/Library/Streamlit)]]

![[topics/Library/Qdrant FastEmbeddings)]]

![[topics/Library/Chroma)]]

![[topics/Model/Mistral 7B)]]

![[topics/Tool/Ollama)]]

![[topics/Library/RecursiveCharacterSplitter)]]

![[topics/Library/PyPDFLoader)]]