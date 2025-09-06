---
type: Library
---

DataTrove is a large-scale data processing library used for processing, filtering, and deduplicating text data. It includes tools for url filtering, text extraction, language filtering, quality filtering, deduplication, and PII formatting. DataTrove is used in the processing pipeline for the FineWeb dataset and is optimized for low memory usage, making it suitable for large workloads such as processing training data for large language models (LLMs). DataTrove pipelines are platform-agnostic, running locally or on slurm clusters, and include features for logging, data management, and custom block creation.