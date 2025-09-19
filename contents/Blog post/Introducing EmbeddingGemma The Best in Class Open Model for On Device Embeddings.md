---
already_read: false
link: https://developers.googleblog.com/en/introducing-embeddinggemma/
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- Natural_Language_Processing
- Large_Language_Model
type: Content
upload_date: '2025-09-19'
---

https://developers.googleblog.com/en/introducing-embeddinggemma/
## Summary

EmbeddingGemma is a new open embedding model designed for on-device AI, offering best-in-class performance for its size. Key features include:

- **Efficiency**: 308 million parameters, runs on less than 200MB of RAM with quantization.
- **Multilingual**: Supports over 100 languages, based on Gemma 3 architecture.
- **Flexibility**: Customizable output dimensions (768 to 128) and 2K token context window.
- **Offline Capability**: Works without an internet connection, ensuring privacy and security.
- **Integration**: Compatible with popular tools like sentence-transformers, llama.cpp, MLX, and more.

EmbeddingGemma excels in tasks like Retrieval Augmented Generation (RAG) and semantic search, providing high-quality embeddings for accurate and reliable on-device applications. It is optimized for speed and efficiency, with inference times under 15ms on EdgeTPU. Developers can fine-tune the model for specific domains or languages. The model is available on platforms like Hugging Face, Kaggle, and Vertex AI, with extensive documentation and integration guides.
## Links

- [EmbeddingGemma on LMStudio](https://lmstudio.ai/models/google/embedding-gemma-300m) : EmbeddingGemma model on LMStudio, a platform for running large language models locally.
- [EmbeddingGemma Inference with Sentence Transformers](https://ai.google.dev/gemma/docs/embeddinggemma/inference-embeddinggemma-with-sentence-transformers) : Guide on how to perform inference with EmbeddingGemma using Sentence Transformers.
- [EmbeddingGemma on Hugging Face](https://huggingface.co/collections/google/embeddinggemma-68b9ae3a72a82f0562a80dc4) : EmbeddingGemma model collection on Hugging Face, a platform for sharing and discovering machine learning models.
- [EmbeddingGemma on Docker Hub](https://hub.docker.com/r/ai/embeddinggemma) : EmbeddingGemma model on Docker Hub, a platform for sharing and discovering containerized applications.
- [EmbeddingGemma on Vertex AI](https://console.cloud.google.com/vertex-ai/publishers/google/model-garden/embeddinggemma) : EmbeddingGemma model on Vertex AI, Google's unified artificial intelligence platform.

## Topics

![[topics/Model/EmbeddingGemma]]

![[topics/Concept/Retrieval Augmented Generation RAG]]

![[topics/Concept/Matryoshka Representation Learning MRL]]

![[topics/Concept/Quantization Aware Training QAT]]