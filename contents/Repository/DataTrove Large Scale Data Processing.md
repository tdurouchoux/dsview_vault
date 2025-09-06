---
already_read: false
link: https://github.com/huggingface/datatrove
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2024-02-08'
---

https://github.com/huggingface/datatrove
## Summary

DataTrove is a library designed for processing, filtering, and deduplicating large-scale text data. It offers a collection of prebuilt processing blocks and a framework for adding custom functionality. Key features include platform-agnostic pipelines that can run locally or on a Slurm cluster, low memory usage, and support for various file systems through fsspec.

The library supports multiple executors for different environments:
- **LocalPipelineExecutor**: Runs pipelines on a local machine with configurable tasks and workers.
- **SlurmPipelineExecutor**: Launches pipelines on a Slurm cluster with options for task distribution and dependencies.
- **RayPipelineExecutor**: Executes pipelines on a Ray cluster with parallel task management.

Pipelines are composed of blocks that process data in the Document format, which includes text, a unique ID, and metadata. Blocks can be readers, writers, extractors, filters, stats, tokens, or deduplication blocks. The library also supports custom blocks and functions for specific processing needs.

DataTrove provides detailed logging and statistics collection, with options for colorization and distributed stats merging. It supports various data sources and destinations through fsspec, and includes practical guides for common tasks like reading data, filtering, saving, and deduplicating.

The library is open-source under the Apache-2.0 license and includes examples, contributing guidelines, and citation information.
## Links

- [Hugging Face FineWeb Dataset](https://huggingface.co/datasets/HuggingFaceFW/fineweb) : The Hugging Face FineWeb dataset, which is referenced in the quickstart examples for DataTrove.
- [SGLang GitHub Repository](https://github.com/sgl-project/sglang) : The SGLang GitHub repository, which is mentioned in the context of synthetic data generation using the InferenceRunner block.
- [Trafilatura Documentation](https://trafilatura.readthedocs.io/en/latest/) : The Trafilatura documentation, which is referenced as a commonly used extractor in DataTrove for extracting text content from raw HTML.

## Topics

![](topics/Library/DataTrove)