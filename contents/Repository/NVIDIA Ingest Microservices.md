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

NVIDIA Ingest is a set of early access microservices designed for parsing unstructured documents, such as PDFs and other enterprise files, into structured metadata and text for integration into retrieval systems. Key features include:

- **Document Processing**: Supports various file types (PDF, DOCX, PPTX, images) and utilizes multiple extraction methods to optimize for throughput and accuracy.
- **Microservices Architecture**: Allows for parallel processing of documents, classifying content into categories like text, tables, and images, and contextualizing it using OCR.
- **Flexible Configuration**: Users can define ingestion tasks via JSON job descriptions and retrieve results in a structured format.
- **Deployment Requirements**: Requires NVIDIA GPUs (A100 or H100), Docker, and specific software dependencies (e.g., CUDA Toolkit, Python 3.10).
- **Installation and Usage**: Users can set up the service using Docker Compose, submit jobs through a Python client or CLI, and inspect results in JSON format.

The repository includes documentation, examples, and a structured codebase for further development and customization.
## Links

1. [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) - A rich OCR tool that can be used for extracting text from images and documents, relevant for the document parsing capabilities of NVIDIA Ingest.
2. [Milvus](https://milvus.io/) - An open-source vector database that can be used for storing embeddings generated from extracted content, which is a feature of NVIDIA Ingest.
3. [pdfservices-sdk](https://pypi.org/project/pdfservices-sdk/) - A Python SDK for Adobe PDF services, useful for document processing and extraction tasks.
4. [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) - A high-performance object detection algorithm that can be utilized for extracting tables and charts from documents, relevant to NVIDIA Ingest's functionality.
5. [Llama-3.2-1B](https://huggingface.co/meta-llama/Llama-3.2-1B) - A tokenizer model that can be used for text processing tasks, which is part of the extraction pipeline in NVIDIA Ingest.
## Topics

![](topics/Library/NVIDIA%20Ingest)

![](topics/Tool/nv%20ingest%20cli)

![](topics/Concept/Document%20Ingestion)

![](topics/Platform/Docker)

![](topics/Dataset/Multi%20modal%20Document%20Types)