---
already_read: true
link: https://www.daft.ai/
read_priority: 0
relevance: 5
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-08-17'
---

https://www.daft.ai/

## Summary

Daft is an open-source, multimodal data engine designed to streamline AI pipelines from raw data to training-ready datasets at scale.

**Core Features**
- Multimodal-native: processes video, images, audio, sensor data, and structured metadata in a single dataframe.
- Unified CPU/GPU pipelines: runs GPU inference/embeddings alongside CPU tasks with automatic scheduling and batching.
- Pandas/Spark-like Python API: familiar operations (filter, transform, aggregate, write) with no new framework to learn.

**Key Advantages**
- Open-source (Apache 2.0) with 5k+ GitHub stars, used in production by Amazon, Essential AI, and others.
- Bring-your-own models, storage, and infrastructure for flexible deployment.
- Native model operators: embeddings, LLM extraction, and structured outputs as first-class operations (supports OpenAI, Hugging Face, custom models).
- Multimodal column types: images, video, audio, text, and embeddings treated as native columns.
- Local-to-production consistency: same code runs on a laptop or scales to a cluster without rewrites.
- Managed UDF runtime: automatic batching, retries, error handling, and zero-copy execution via Apache Arrow.
- 5x lower memory footprint than alternatives (e.g., Spark, Pandas), preventing OOM errors.
- Rust core: high-speed decoding, transforms, and joins at TB scale without Python overhead.

**Performance Highlights**
- Amazon: 24% efficiency gain in critical jobs, saving 40k+ years of EC2 vCPU time annually.
- Essential AI: scaled vLLM-inference pipeline to 32k sustained requests/sec/VM.
- Together AI: 10x speedup for fuzzy deduplication on 100TB+ text datasets.
- Anthropic: handled 16k small Parquet files in self-hosted S3 seamlessly.

**Ecosystem Integrations**
- Compatible with Apache Hudi, Iceberg, AWS, Azure, Delta Lake, Google Cloud, Unity Catalog, Ray, Pandas, PyTorch.

## Links

- [Daft Documentation](https://docs.daft.ai/en/stable/) : Comprehensive documentation for Daft, covering installation, API references, integrations (e.g., Delta Lake, Iceberg, AWS, Azure), tutorials, and distributed computing features. Essential for understanding Daft's capabilities and usage.
- [Daft GitHub Repository](https://github.com/Eventual-Inc/Daft) : The official GitHub repository for Daft, providing open-source access to the codebase, issue tracking, and community contributions. Includes examples, benchmarks, and integration with tools like PyTorch and Pandas.
- [Daft Integrations with Delta Lake](https://docs.daft.ai/en/stable/integrations/delta_lake/) : Documentation on how Daft integrates with Delta Lake, enabling ACID transactions and scalable data processing for large-scale datasets.
- [Daft Integrations with Apache Iceberg](https://docs.daft.ai/en/stable/integrations/iceberg/) : Guide to using Daft with Apache Iceberg, a table format for large-scale analytics, supporting schema evolution and partition evolution.
- [Daft Integrations with AWS](https://docs.daft.ai/en/stable/integrations/aws/) : Documentation on Daft's AWS integrations, including S3 configuration, IAM roles, and best practices for running Daft pipelines in AWS environments.


## Topics

![[topics/Library/Daft]]

![[topics/Platform/AWS]]

![[topics/Concept/Parquet]]

![[topics/Platform/Azure]]

![[topics/Platform/Google Cloud]]

![[topics/Concept/Ray]]

![[topics/Library/Pandas]]

![[topics/Library/PyTorch]]

![[topics/Platform/Unity Catalog]]