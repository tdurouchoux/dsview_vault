---
already_read: false
link: https://arxiv.org/pdf/1810.04805
read_priority: 5
relevance: 0
source: null
tags:
- Natural_Language_Processing
- Deep_Learning
type: Content
upload_date: '2025-02-20'
---

![](artefacts/1810.04805)
## Summary

BERT (Bidirectional Encoder Representations from Transformers) is a novel language representation model that pre-trains deep bidirectional representations from unlabeled text by conditioning on both left and right contexts. This approach allows BERT to achieve state-of-the-art results across various natural language processing (NLP) tasks, including question answering and language inference, with minimal task-specific architecture changes.

Key contributions of BERT include:
- **Bidirectional Pre-training**: BERT employs a masked language model (MLM) objective, which randomly masks tokens in the input and predicts them based on context, enabling deep bidirectional representations.
- **Next Sentence Prediction (NSP)**: This task helps the model understand relationships between sentence pairs, which is crucial for tasks like question answering.
- **Unified Architecture**: BERT maintains the same architecture for both pre-training and fine-tuning, simplifying the process of adapting to various tasks.

BERT has demonstrated significant improvements on eleven NLP benchmarks, including:
- GLUE benchmark score of 80.5%
- MultiNLI accuracy of 86.7%
- SQuAD v1.1 F1 score of 93.2
- SQuAD v2.0 F1 score of 83.1

The model architecture consists of a multi-layer bidirectional Transformer encoder, with two primary sizes: BERTBASE (12 layers, 110M parameters) and BERTLARGE (24 layers, 340M parameters). The pre-training phase utilizes a large corpus, including BooksCorpus and English Wikipedia, while fine-tuning is performed on specific downstream tasks with labeled data.

BERT's effectiveness is attributed to its ability to leverage both left and right context in all layers, contrasting with previous models that used unidirectional approaches. The results indicate that BERT's architecture and training methodology significantly enhance performance across a wide range of NLP tasks.
## Topics

![](topics/Model/BERT)

![](topics/Concept/Masked%20Language%20Model%20MLM)

![](topics/Concept/Next%20Sentence%20Prediction%20NSP)

![](topics/Dataset/GLUE)

![](topics/Dataset/SQuAD)