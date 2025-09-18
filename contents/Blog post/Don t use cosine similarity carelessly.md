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

The blog post discusses the pitfalls of using cosine similarity carelessly in data science, particularly with embeddings from Large Language Models (LLMs). Key points include:

1. **Embeddings and Cosine Similarity**:
   - Embeddings capture relationships between items, but cosine similarity may not always reflect the intended similarity.
   - Cosine similarity is the cosine of the angle between vectors, often used to compare vectors in high-dimensional spaces.

2. **Problems with Cosine Similarity**:
   - It's a quick fix that may mask deeper problems and doesn't always represent meaningful metrics.
   - It's related to Pearson correlation but skips the mean centering step.
   - It may not align with the training objective or the actual similarity needed.

3. **When It Falls Apart**:
   - Cosine similarity may match questions to questions rather than questions to answers.
   - It can be distracted by superficial patterns like writing style and typos rather than meaning.

4. **Better Approaches**:
   - Use LLM queries to compare entries directly for more meaningful comparisons.
   - Create task-specific embeddings through fine-tuning or transfer learning.
   - Pre-process text with prompts or rewriting to focus on relevant aspects before embedding.

5. **Recap**:
   - Cosine similarity provides a number between -1 and 1 but isn't a probability.
   - Models aren't always trained with cosine similarity, so results may vary.
   - To use vector similarity effectively, consider training custom embeddings, engineering prompts, or cleaning and standardizing text.

The post emphasizes the importance of understanding the limitations of cosine similarity and exploring alternative methods for more accurate and meaningful similarity measures.
## Links

- [OpenAI Embedding Models and API Updates](https://openai.com/index/new-embedding-models-and-api-updates/) : This link points to the OpenAI blog post about new embedding models and API updates, which is relevant to the content discussing embeddings and cosine similarity.
- [Text and Code Embeddings by Contrastive Pre-Training](https://cdn.openai.com/papers/Text_and_Code_Embeddings_by_Contrastive_Pre_Training.pdf) : This link points to a research paper on text and code embeddings by contrastive pre-training, which is relevant to the content discussing embeddings and their applications.
- [Thinking in Tensors, Writing in PyTorch](https://github.com/stared/thinking-in-tensors-writing-in-pytorch) : This link points to a GitHub repository for a series on thinking in tensors and writing in PyTorch, which is relevant to the content discussing the use of PyTorch for machine learning tasks.
- [GLove Embeddings](https://nlp.stanford.edu/projects/glove/) : This link points to the GLove embeddings project, which is relevant to the content discussing the use of embeddings and cosine similarity.
- [Levenshtein Distance](https://en.wikipedia.org/wiki/Levenshtein_distance) : This link points to the Wikipedia page for Levenshtein distance, which is relevant to the content discussing string similarity and its limitations.

## Topics

![[topics/Concept/Retrieval Augmented Generation RAG)]]

![[topics/Concept/Text Embeddings)]]

![[topics/Concept/Prompt Engineering)]]

![[topics/Concept/Cosine Similarity)]]

![[topics/Concept/Sentence Embeddings)]]