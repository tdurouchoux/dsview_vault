---
already_read: false
link: https://blog.duy-huynh.com/build-your-own-rag-and-run-them-locally/
read_priority: 1
source: null
tags:
- Large_Language_Model
- Generative_AI
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

The article suggests enhancements such as adding memory to the conversation chain, allowing multiple file uploads, experimenting with different LLM models, and improving the RAG pipeline.

Overall, the guide provides a high-level overview of creating a local RAG application, encouraging further exploration and development.
## Links

1. [Building RAG-based LLM Applications for Production](https://www.anyscale.com/blog/a-comprehensive-guide-for-building-rag-based-llm-applications-part-1?ref=blog.duy.dev) - A guide on developing and productionizing a retrieval augmented generation (RAG) based LLM application, focusing on scale and evaluation.
2. [Retrieval Augmented Generation (RAG): A Comprehensive Guide](https://www.datastax.com/guides/what-is-retrieval-augmented-generation?ref=blog.duy.dev) - An explanation of RAG, its use cases, and how vector search and vector databases contribute to its functionality.
3. [What is retrieval-augmented generation? | IBM Research Blog](https://research.ibm.com/blog/retrieval-augmented-generation-RAG?ref=blog.duy.dev) - An overview of the RAG framework for retrieving facts to ground LLMs and enhance decision-making insights.
4. [Langchain](https://python.langchain.com/docs/get_started/introduction?ref=blog.duy.dev) - Documentation for Langchain, a library used for building applications with LLMs, including RAG implementations.
5. [Streamlit](https://streamlit.io/?ref=blog.duy.dev) - A framework for building interactive web applications in Python, which is used in the project for creating the user interface.
## Topics

- [[topics/Library/LangChain]]
- [[topics/Library/Ollama]]
- [[topics/Library/Streamlit]]
- [[topics/Library/Chroma]]
- [[topics/Model/Mistral-7B]]