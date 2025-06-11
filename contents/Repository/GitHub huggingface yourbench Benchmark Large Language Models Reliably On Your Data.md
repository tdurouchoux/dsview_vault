---
already_read: false
link: https://github.com/huggingface/yourbench
read_priority: 5
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2025-06-11'
---

https://github.com/huggingface/yourbench
## Summary

YourBench is an open-source framework designed for the dynamic generation of domain-specific benchmarks for evaluating large language models (LLMs) without the need for manual annotation. It addresses challenges with traditional benchmarks that often become stale or biased due to training data, enabling the creation of customized evaluation sets based on user-provided data.

Key features include:

- **Dynamic and Automated Benchmarking**: It generates question-answer pairs grounded in actual documents, allowing for timely and relevant evaluations tailored to specific domains.
- **Cost-Effective**: YourBench can replicate existing benchmarks efficiently, as demonstrated in its ability to mirror subsets of MMLU at a minimal cost while maintaining model performance rankings.
- **Flexible Installation**: Available on PyPI for ease of installation, with options for both stable and developmental versions.
- **Multi-Stage Process**: Includes steps for document ingestion, summarization, chunking, question generation, deduplication, and analysis, ensuring high-quality outputs.
- **Extensible Pipeline**: Users can customize their evaluation pipeline through a YAML configuration, allowing for various models and processing parameters.
- **Robust Analysis**: Provides metrics to evaluate dataset characteristics and question quality.

Users can run the framework via command line or use a web demo that allows for easy document uploads and benchmark generation without local installation. The tool is positioned to support diverse applications and help keep LLMs updated with relevant, domain-specific knowledge. 

YourBench is licensed under the Apache 2.0 License and welcomes community contributions, enhancing its capabilities for custom evaluation processes.
## Links

- [YourBench Documentation](https://github.com/huggingface/yourbench/tree/main/docs) : Official documentation for the YourBench framework, detailing installation, usage, and configuration.
- [Hugging Face Demo for YourBench](https://huggingface.co/spaces/yourbench/demo) : A web demo by Hugging Face to try out YourBench for generating custom evaluation sets.
- [YourBench Advanced Space](https://huggingface.co/spaces/yourbench/advanced) : An advanced demo allowing users to customize and use their own models with the YourBench pipeline.
- [Research Paper on YourBench](https://arxiv.org/abs/2504.01833) : The research paper that describes the YourBench framework and its capabilities in detail.
- [Tempora Dataset for Time-Sensitive Topics](https://huggingface.co/datasets/sumuks/tempora) : A dataset that can be used in conjunction with YourBench for evaluations related to time-sensitive topics.

## Topics

![](topics/Library/YourBench)

![](topics/Concept/Dynamic%20Benchmarking)

![](topics/Tool/Hugging%20Face)

![](topics/Concept/Question%20Generation)

![](topics/Concept/Data%20Ingestion)