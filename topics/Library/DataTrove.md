---
type: Library
---

A library used for cleaning and preparing large datasets at scale. It is utilized in the dataset pipeline to process Kaggle notebooks, ensuring they are ready for training data science agents. DataTrove is a library designed for processing, filtering, and deduplicating text data at a large scale. It offers prebuilt processing blocks and a framework for adding custom functionality. The library supports various file systems through fsspec and is optimized for low memory usage, making it suitable for large workloads such as processing training data for large language models (LLMs). DataTrove pipelines are platform-agnostic, running locally or on slurm clusters, and include features for logging, data management, and custom block creation.