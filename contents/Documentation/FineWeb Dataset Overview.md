---
already_read: false
link: https://huggingface.co/datasets/HuggingFaceFW/fineweb/blob/main/README.md
read_priority: 1
source: null
tags:
- Natural_Language_Processing
type: Content
upload_date: '2024-04-29'
---

https://huggingface.co/datasets/HuggingFaceFW/fineweb/blob/main/README.md
## Summary

The FineWeb dataset consists of over 15 trillion tokens of cleaned and deduplicated English web data sourced from CommonCrawl, optimized for large language model (LLM) performance. It aims to provide a high-quality, open-source pretraining dataset, surpassing the performance of existing datasets like RefinedWeb, C4, and The Pile.

Key features include:
- **Dataset Structure**: Contains various configurations for different sample sizes (10B, 100B, 350B tokens) and includes all CommonCrawl dumps from 2013 to 2024.
- **Data Processing**: Utilizes the datatrove library for processing, which includes URL filtering, text extraction, language filtering, quality checks, and deduplication.
- **Performance Evaluation**: Evaluated against multiple benchmarks, demonstrating superior performance compared to other datasets.
- **Considerations**: Acknowledges potential biases and limitations, including the presence of toxic content and the lack of code-related data.
- **Licensing**: Released under the Open Data Commons Attribution License (ODC-By) v1.0.

Future work will focus on improving dataset quality and expanding open-source training datasets. The dataset and its processing code are available for public use, promoting transparency and accessibility in model training.
## Links

1. [datatrove](https://github.com/huggingface/datatrove/) - A library for large-scale data processing, optimized for LLM performance.
2. [RefinedWeb](https://huggingface.co/papers/2306.01116) - A paper discussing the RefinedWeb dataset, which is related to the FineWeb dataset.
3. [C4](https://huggingface.co/datasets/allenai/c4) - A large dataset for training language models, often compared with FineWeb.
4. [The Pile](https://huggingface.co/datasets/EleutherAI/pile) - A diverse dataset for language modeling, used for benchmarking against FineWeb.
5. [RedPajama2](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-V2) - Another dataset for training language models, relevant for comparison with FineWeb.
## Topics

- [[topics/Library/DataTrove]]
- [[topics/Library/Hugging Face]]
- [[topics/Library/datasets]]
- [[topics/Concept/Data Processing]]