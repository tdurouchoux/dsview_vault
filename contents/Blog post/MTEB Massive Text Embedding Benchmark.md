---
already_read: false
link: https://huggingface.co/blog/mteb
read_priority: 4
relevance: 0
source: null
tags:
- Natural_Language_Processing
type: Content
upload_date: '2025-02-20'
---

https://huggingface.co/blog/mteb
## Summary

MTEB (Massive Text Embedding Benchmark) is a comprehensive benchmark for evaluating text embedding models across 8 tasks and 56 datasets, with support for up to 112 languages. It aims to help users find the best embedding model for their specific needs. The benchmark includes a leaderboard, a paper detailing the tasks and datasets, and a GitHub repository for benchmarking and submitting models.

Text embeddings are crucial for various NLP applications, as they convert text into numerical vectors that encode semantic information. The quality of these embeddings depends heavily on the model used. MTEB categorizes models into three groups based on their speed and performance: maximum speed (e.g., Glove), balanced (e.g., all-mpnet-base-v2), and maximum performance (e.g., ST5-XXL).

To benchmark a model, users can install the MTEB library, run evaluations on chosen datasets, and submit results to the leaderboard by adding metadata to the model's README.md on the Hugging Face Hub. The benchmark is designed to be extensible, welcoming contributions for new tasks, datasets, metrics, or leaderboard additions.
## Links

- [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) : The leaderboard for the Massive Text Embedding Benchmark (MTEB), providing a holistic view of the best text embedding models across various tasks.
- [MTEB GitHub Repository](https://github.com/embeddings-benchmark/mteb) : The GitHub repository containing the code for benchmarking and submitting any model to the MTEB leaderboard.
- [MTEB Paper](https://arxiv.org/abs/2210.07316) : The research paper providing background on the tasks and datasets in MTEB and analyzing leaderboard results.

## Topics

![](topics/Concept/Text%20Embeddings)

![](topics/Dataset/MTEB)

![](topics/Library/MTEB%20Library)