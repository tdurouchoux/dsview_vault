---
already_read: false
link: https://huggingface.co/datasets/HuggingFaceFW/fineweb/blob/main/README.md
read_priority: 1
relevance: 0
source: null
tags:
- Natural_Language_Processing
type: Content
upload_date: '2024-04-29'
---

https://huggingface.co/datasets/HuggingFaceFW/fineweb/blob/main/README.md
## Summary

The 🍷 FineWeb dataset is a large-scale, cleaned, and deduplicated English web data collection from CommonCrawl, optimized for LLM performance. It consists of over 18.5 trillion tokens and includes data from CommonCrawl dumps since 2013. The dataset is processed using the 🏭 datatrove library and is licensed under the ODC-By 1.0 license.

Key features of FineWeb include:
- Performance improvements over RefinedWeb and other high-quality web datasets.
- Availability of the full dataset and smaller sample versions (350BT, 100BT, 10BT).
- Detailed breakdown by dump/crawl, including disk size and token count.
- Dataset performance evaluation and ablations, with hyper-parameters and benchmarks provided.
- Comparison with other datasets like RefinedWeb, C4, Dolma v1.6, The Pile, SlimPajama, and RedPajama2.

The dataset is structured with fields such as text, id, dump, url, date, file_path, language, language_score, and token_count. It is intended for research and pretraining of large language models, with efforts made to minimize NSFW and toxic content. The dataset is released under the Open Data Commons Attribution License (ODC-By) v1.0, and future work aims to expand and improve the dataset.
## Links

- [FineWeb Dataset on Hugging Face](https://huggingface.co/datasets/HuggingFaceFW/fineweb) : The main repository for the FineWeb dataset, providing access to the dataset, documentation, and related resources.
- [Common Crawl Overview](https://commoncrawl.org/overview) : Overview of Common Crawl, the source of the web data used in the FineWeb dataset.
- [FineWeb Blog Post](https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1) : Blog post detailing the creation and processing of the FineWeb dataset, including insights into the deduplication methods and performance evaluations.

## Topics

![](topics/Dataset/FineWeb)

![](topics/Platform/Hugging%20Face)

![](topics/Library/DataTrove)

![](topics/Dataset/Common%20Crawl)

![](topics/Concept/Data%20Deduplication)