---
already_read: false
link: https://github.com/NVIDIA/nv-ingest
read_priority: 2
relevance: 0
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2025-03-11'
---

https://github.com/NVIDIA/nv-ingest
## Summary

NeMo Retriever Extraction is a scalable, performance-oriented microservice for document content and metadata extraction, utilizing NVIDIA NIM microservices. It extracts text, tables, charts, and images from various file types (e.g., PDF, DOCX, PNG) and supports downstream generative applications. The service can optionally compute embeddings and store them in a vector database like Milvus. It has evolved from using Cached and Deplot to the yolox-graphic-elements NIM, enabling operation on a single GPU. The extraction process involves parallelizing document splitting, artifact classification, OCR, and contextualization into a JSON schema. The service is deployed using Docker Compose or Kubernetes for scalability and supports multiple extraction methods for balancing throughput and accuracy. It also offers various preprocessing and postprocessing operations, including text splitting, embedding generation, and image offloading. The GitHub repository includes documentation, examples, and source code for the service.
## Links

- [NVIDIA NeMo Retriever Extraction Documentation](https://docs.nvidia.com/nemo/retriever/latest/extraction/overview/) : Official documentation for NVIDIA NeMo Retriever Extraction, providing detailed information on its features, setup, and usage.
- [NVIDIA NGC API Keys Setup](https://org.ngc.nvidia.com/setup/api-keys) : Guide on setting up API keys for NVIDIA NGC, which is necessary for accessing certain NVIDIA services and resources.
- [NVIDIA Build - NeMo Retriever Parse](https://build.nvidia.com/nvidia/nemoretriever-parse) : NVIDIA Build page for NeMo Retriever Parse, providing access to the tool and related resources.

## Topics

![](topics/Library/NeMo%20Retriever%20extraction)

![](topics/Library/NVIDIA%20NIM%20microservices)

![](topics/Library/yolox%20graphic%20elements%20NIM)

![](topics/Library/pdfium)

![](topics/Library/nemoretriever%20parse)

![](topics/Library/Unstructured%20io)

![](topics/Library/Adobe%20Content%20Extraction%20Services)

![](topics/Library/Milvus)

![](topics/Library/Llama%203%202%201B%20tokenizer)