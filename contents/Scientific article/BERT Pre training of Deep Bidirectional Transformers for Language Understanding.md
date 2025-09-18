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

https://arxiv.org/pdf/1810.04805
## Summary

The paper introduces BERT (Bidirectional Encoder Representations from Transformers), a new language representation model designed to pre-train deep bidirectional representations from unlabeled text. Unlike previous models, BERT jointly conditions on both left and right context in all layers, allowing it to be fine-tuned with minimal task-specific architecture modifications for a wide range of tasks.

Key points and takeaways:

1. **Model Architecture**: BERT uses a multi-layer bidirectional Transformer encoder, with two model sizes: BERTBASE (12 layers, 768 hidden units, 110M parameters) and BERTLARGE (24 layers, 1024 hidden units, 340M parameters).

2. **Pre-training Tasks**: BERT is pre-trained using two unsupervised tasks:
   - **Masked Language Model (MLM)**: Randomly masks some tokens and predicts the original vocabulary id of the masked words based only on its context.
   - **Next Sentence Prediction (NSP)**: Predicts whether the second sentence is the actual next sentence that follows the first sentence or a random sentence from the corpus.

3. **Fine-tuning**: BERT can be fine-tuned for various tasks by adding a single output layer and fine-tuning all parameters end-to-end. It achieves state-of-the-art results on 11 NLP tasks, including GLUE, SQuAD v1.1, SQuAD v2.0, and SWAG.

4. **Ablation Studies**: The paper demonstrates the importance of bidirectional pre-training, showing that BERT outperforms left-to-right models and models without the NSP task. It also shows that larger models lead to strict accuracy improvements across all tasks.

5. **Feature-based Approach**: BERT can also be used in a feature-based approach, where contextual embeddings are extracted and used as input to a task-specific model. This approach performs competitively with state-of-the-art methods.

6. **Comparison with ELMo and OpenAI GPT**: BERT is compared with ELMo and OpenAI GPT, highlighting the differences in architecture, pre-training tasks, and fine-tuning procedures. The paper argues that the bidirectional pre-training and the two pre-training tasks account for the majority of the empirical improvements.

In summary, BERT is a powerful and versatile language representation model that achieves state-of-the-art results on a wide range of NLP tasks. Its bidirectional pre-training and the use of two unsupervised tasks make it particularly effective for fine-tuning on downstream tasks.
## Links


## Topics

![[topics/Model/BERT)]]

![[topics/Concept/Masked Language Model MLM)]]

![[topics/Concept/Transformer Architecture)]]

![[topics/Concept/Next Sentence Prediction NSP)]]