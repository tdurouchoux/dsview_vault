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

The 🍷 FineWeb dataset is a large-scale, cleaned, and deduplicated English web data collection from CommonCrawl, optimized for LLM performance. It consists of over 18.5 trillion tokens and is designed to outperform other high-quality web datasets like C4, Dolma-v1.6, The Pile, SlimPajama, and RedPajama2. The dataset is released under the ODC-By 1.0 license and includes all CommonCrawl dumps since 2013. The processing pipeline, which uses the 🏭 datatrove library, involves url filtering, text extraction, language filtering, quality filtering, deduplication, and PII formatting. The dataset is evaluated using a series of 1.8B parameter models trained on 27 billion tokens, with benchmarks selected for their high signal-to-noise ratio. The dataset is structured with fields for text, unique identifier, dump, url, date, file path, language, language score, and token count. Future work includes continuing to improve the dataset and expanding efforts to create open-source high-quality training datasets.
## Links

- [FineWeb Dataset Repository](https://huggingface.co/datasets/HuggingFaceFW/fineweb) : The main repository for the FineWeb dataset, containing detailed information about the dataset, its structure, and usage instructions.
- [FineWeb Dataset Evaluation Results](https://huggingface.co/datasets/HuggingFaceFW/fineweb/blob/main/eval_results.csv) : Evaluation results for the FineWeb dataset, providing insights into its performance and quality.
- [FineWeb Dataset Blog Post](https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1) : A blog post detailing the creation and processing of the FineWeb dataset, including insights into the methodology and results.

## Topics

![](topics/Dataset/FineWeb)

![](topics/Dataset/Common%20Crawl)

![](topics/Library/DataTrove)

![](topics/Concept/Deduplication)

![](topics/Concept/Text%20Extraction)

![](topics/Concept/Language%20Filtering)