---
already_read: false
link: https://github.com/huggingface/datatrove
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
- Data_Analysis
type: Content
upload_date: '2024-02-08'
---

https://github.com/huggingface/datatrove
## Summary

DataTrove is a library designed for processing, filtering, and deduplicating large-scale text data. It offers prebuilt processing blocks and a framework for custom functionality, with pipelines that are platform-agnostic and can run locally or on a Slurm cluster. Key features include low memory usage, support for various file systems through fsspec, and the ability to track and resume tasks.

The library provides several types of pipeline blocks, including readers, writers, extractors, filters, stats, tokens, and deduplication blocks. Pipelines are defined as lists of these blocks and can be executed using different executors, such as LocalPipelineExecutor, SlurmPipelineExecutor, and RayPipelineExecutor. Each executor has specific options for managing tasks and parallelism.

DataTrove supports a wide variety of input/output sources and provides practical guides for common tasks like reading data, generating synthetic data, extracting text, filtering data, saving data, deduplicating data, and collecting summary statistics. Custom blocks can be defined by inheriting from PipelineStep or its subclasses.

The library is open-source under the Apache-2.0 license and includes contributions from multiple developers. Installation is straightforward using pip, with various flavors available for different dependencies. The library also provides examples and documentation for common use cases.
## Links

- [DataTrove Documentation](https://filesystem-spec.readthedocs.io/en/latest/) : Documentation for fsspec, a library used by DataTrove for supporting various file systems.
- [FineWeb Dataset](https://huggingface.co/datasets/HuggingFaceFW/fineweb) : Hugging Face dataset page for FineWeb, which is mentioned in the quickstart examples of DataTrove.
- [Trafilatura Documentation](https://trafilatura.readthedocs.io/en/latest/) : Documentation for Trafilatura, a library used by DataTrove for text extraction from HTML.

## Topics

![[topics/Concept/Slurm]]

![[topics/Concept/fsspec]]

![[topics/Concept/Ray]]

![[topics/Concept/Pipeline Processing Blocks]]

![[topics/Library/DataTrove]]