---
already_read: true
link: https://p.migdal.pl/blog/2025/01/dont-use-cosine-similarity
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Natural_Language_Processing
- Large_Language_Model
type: Content
upload_date: '2025-01-22'
---

https://p.migdal.pl/blog/2025/01/dont-use-cosine-similarity
## Summary

- **Main Points:**
  - Cosine similarity is often used as a quick fix for vector comparisons, but it can lead to misleading results if not used carefully.
  - Embeddings capture similarities, but they may reflect the wrong kind of similarity (e.g., matching questions to questions rather than questions to answers).
  - Cosine similarity is the cosine of the angle between two vectors and is calculated as the dot product of normalized vectors.
  - It has appealing properties but can be misleading, as the values do not represent probabilities or meaningful metrics.
  - Cosine similarity is related to Pearson correlation, but it skips the mean centering step.
  - Problems arise when the training objective differs from what is actually cared about or when the model has not been exposed to cosine similarity.
  - Cosine similarity may not capture the right kind of similarity, as it smashes nuanced views into a single number.
  - In practice, cosine similarity may not work well for tasks like finding answers to questions, as it may match questions to other questions rather than providing plausible answers.
  - Alternative approaches include using LLM queries to compare entries directly, fine-tuning or transfer learning to create task-specific embeddings, prompt engineering, and preprocessing text before embedding.
  - Key takeaways: Cosine similarity provides a number between -1 and 1 but should not be mistaken for a probability. Most models are not trained using cosine similarity, and even when they are, the kind of similarity learned may not match the user's needs. Effective use of vector similarity involves training custom embeddings, engineering prompts, and cleaning/standardizing text before embedding.
## Links

- [OpenAI Embedding Models](https://platform.openai.com/docs/guides/embeddings) : Documentation on OpenAI's embedding models, including text-embedding-3-large, which is used to generate vectors for text similarity analysis.
- [Thinking in Tensors, Writing in PyTorch](https://github.com/stared/thinking-in-tensors-writing-in-pytorch) : A GitHub repository containing tutorials and exercises on using PyTorch for tensor operations and deep learning, relevant to the discussion on embeddings and cosine similarity.
- [Text and Code Embeddings by Contrastive Pre-Training](https://cdn.openai.com/papers/Text_and_Code_Embeddings_by_Contrastive_Pre_Training.pdf) : A research paper on contrastive pre-training for text and code embeddings, which is relevant to the topic of embeddings and their applications.

## Topics

![](topics/Concept/Cosine%20Similarity)

![](topics/Concept/Sentence%20Embeddings)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Text%20Embeddings)

![](topics/Concept/Prompt%20Engineering)