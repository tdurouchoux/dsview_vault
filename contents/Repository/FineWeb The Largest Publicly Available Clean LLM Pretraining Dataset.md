---
already_read: false
link: https://huggingface.co/datasets/HuggingFaceFW/fineweb/blob/main/README.md
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2024-04-29'
---

https://huggingface.co/datasets/HuggingFaceFW/fineweb/blob/main/README.md
## Summary

The provided content details the FineWeb dataset created by Hugging Face, which contains over 15 trillion tokens of cleaned and deduplicated English web data obtained from CommonCrawl. The dataset was designed to enhance the performance of large language models (LLMs) and outperforms existing high-quality datasets like RefinedWeb and C4.

Key points include:

- **Dataset Overview**: Offers significant data for LLM training and is openly licensed under ODC-By 1.0.
- **Dataset Creation**: Involves meticulous data processing to filter out low-quality or toxic content using the datatrove library. Various filtering methods, including URL filtering and MinHash deduplication, were implemented.
- **Release Information**: The dataset consists of numerous CommonCrawl dumps and provides configurations for different sample sizes.
- **Performance Evaluation**: Conducted comparative evaluations with several other datasets, demonstrating the effectiveness of FineWeb.
- **Technical Usage**: Provides instructions for downloading and utilizing the dataset through Hugging Face tools, including examples for coding access.
- **Future Directions and Considerations**: Ongoing improvements to dataset quality and transparency in processing methods are planned, alongside attention to the social impact and potential biases within the dataset.

Overall, FineWeb aims to democratize access to high-quality data for model training while maintaining transparency and providing tools for effective use.
## Links

- [FineWeb Dataset on Hugging Face](https://huggingface.co/datasets/HuggingFaceFW/fineweb) : A comprehensive resource for the FineWeb dataset, which includes 15 trillion tokens of web data optimized for LLM performance.
- [Gopher Repetition Filter Code](https://github.com/huggingface/datatrove/blob/9a88bebc86a554f8521faa70b12ad4fa0c227537/src/datatrove/pipeline/filters/gopher_repetition_filter.py) : The source code for the Gopher Repetition Filter used in preprocessing the FineWeb dataset.
- [C4 Dataset on Hugging Face](https://huggingface.co/datasets/allenai/c4) : The C4 dataset, a widely used dataset in NLP, available for researchers and practitioners.
- [EleutherAI’s The Pile Dataset](https://huggingface.co/datasets/EleutherAI/pile) : The Pile, a large, diverse dataset designed for training language models.
- [The Stack Dataset](https://huggingface.co/datasets/bigcode/the-stack-v2) : A dataset designed for training models focused on coding tasks, part of the BigCode initiative.

## Topics

![](topics/Dataset/FineWeb)

![](topics/Library/DataTrove)

![](topics/Library/huggingface_hub)