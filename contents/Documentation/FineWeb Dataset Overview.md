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
- **Dataset Structure**: Contains various configurations for different sample sizes (10B, 100B, 350B tokens) and includes all CommonCrawl dumps since 2013.
- **Data Processing**: Utilizes the datatrove library for processing, which includes URL filtering, text extraction, language filtering, and deduplication.
- **Performance Evaluation**: Evaluated against benchmarks to validate its effectiveness compared to other datasets.
- **Considerations**: Acknowledges potential biases and limitations, including the presence of toxic content and the lack of code-related data.

The dataset is released under the Open Data Commons Attribution License (ODC-By) and aims to enhance accessibility for the machine learning community. Future improvements and expansions of the dataset are planned.
## Links

1. [datatrove GitHub Repository](https://github.com/huggingface/datatrove/) - The official repository for the datatrove library, which is used for processing the FineWeb dataset.
2. [FineWeb Dataset Paper](https://arxiv.org/abs/2406.17557) - The research paper detailing the FineWeb dataset, its creation, and its performance evaluations.
3. [C4 Dataset on Hugging Face](https://huggingface.co/datasets/allenai/c4) - A commonly used dataset for training language models, referenced for comparison with FineWeb.
4. [The Pile Dataset](https://huggingface.co/datasets/EleutherAI/pile) - Another high-quality dataset for language model training, mentioned in the context of dataset comparisons.
5. [RedPajama Dataset](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-V2) - A dataset referenced for its relevance in the context of high-quality web data for training language models.
## Topics

![](topics/Dataset/FineWeb)

![](topics/Library/DataTrove)

![](topics/Library/huggingface_hub)

![](topics/Product/Datasets%20and%20Datasette)

![](topics/Concept/Data%20Processing%20and%20Preprocessing)