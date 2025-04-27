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

NVIDIA Ingest is a set of early access microservices designed to parse large volumes of unstructured documents, such as PDFs and enterprise files, extracting metadata and text to facilitate data retrieval. This tool supports multiple file formats (PDF, DOCX, PPTX, JPEG, etc.) and employs specialized NVIDIA NIMs (neural inference microservices) for content extraction, including text, tables, charts, and images.

Key features include:
- Job specification handling to process documents and extract relevant content.
- Various extraction methods to balance throughput and accuracy.
- Support for pre- and post-processing tasks, like text chunking and embedding generation.
- Parallel processing for efficient document handling.

Installation can be done via Docker Compose or Kubernetes; a library mode is available for smaller workloads. The pipeline involves submitting document ingestion jobs through Python, managing task parallelization, and querying extracted content using vector databases like Milvus.

The repository includes a structured layout with documentation, example code, and necessary configurations for deployment, ensuring easy integration into existing workflows.
## Links

- [NVIDIA NeMo Retriever Extraction Overview](https://docs.nvidia.com/nemo/retriever/extraction/overview/) : Documentation that provides an overview of NVIDIA NeMo's retrieval and extraction capabilities.
- [Adobe PDF Services SDK](https://github.com/adobe/pdfservices-python-sdk?tab=License-1-ov-file) : GitHub repository for Adobe's PDF Services SDK which allows developers to work with PDF files.
- [Milvus Vector Database](https://milvus.io/) : Milvus is an open-source vector database designed for AI applications, enabling efficient storage and retrieval of complex data.
- [Hugging Face Meta-Llama 3.2-1B Model](https://huggingface.co/meta-llama/Llama-3.2-1B) : Page for the Meta-Llama 3.2-1B model hosted on Hugging Face providing tokenizer and model access.
- [PDF Services SDK on PyPI](https://pypi.org/project/pdfservices-sdk/) : Python Package Index page for installing and using the PDF Services SDK.

## Topics

![](topics/Tool/NVIDIA%20Ingest)

![](topics/Library/NV%20Ingest)

![](topics/Concept/Document%20Ingestion)

![](topics/Concept/Content%20Extraction)

![](topics/Concept/Vector%20Database)

![](topics/Tool/Milvus)