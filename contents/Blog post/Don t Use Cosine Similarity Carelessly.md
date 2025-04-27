---
already_read: true
link: https://p.migdal.pl/blog/2025/01/dont-use-cosine-similarity
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Data_Analysis
type: Content
upload_date: '2025-01-22'
---

https://p.migdal.pl/blog/2025/01/dont-use-cosine-similarity
## Summary

Cosine similarity is a commonly used technique in data science for measuring the similarity between vector representations, but it can lead to misleading results if applied blindly. While embeddings, particularly from Large Language Models (LLMs), can capture textual relationships, they may also reflect superficial patterns rather than meaningful semantic connections.

Key points include:

- **Misleading Similarities**: Cosine similarity can associate questions with questions instead of questions with answers, thereby failing to capture true meaning.
- **Dimensional Complexity**: High-dimensional vector spaces complicate interpretation; numerical values from cosine similarity may not represent real probabilities.
- **Normalization and Pearson Correlation**: Cosine similarity is closely related to Pearson correlation, minus mean centering, but can behave unpredictably when vectors are unnormalized.
- **Use Cases and Limitations**: While cosine similarity is useful as a loss function in training models, caution is needed when applying it beyond its intended scope.
- **Contextual Relevance**: The notion of similarity varies across contexts, posing a challenge for the definition of similarity in models.
- **Alternative Approaches**: Instead of relying solely on cosine similarity, it’s beneficial to use task-specific embeddings, fine-tuning, or crafting prompts to focus on relevant features.
- **Preprocessing Techniques**: Cleaning and standardizing text before embedding can significantly improve similarity measurements by removing superficial discrepancies.

Ultimately, while cosine similarity is a useful tool, it should not be the only metric employed; a more nuanced approach that considers context, specific needs, and thorough pre-processing can yield better results in similarity assessments.
## Links

- [OpenAI Embedding Models and API Updates](https://openai.com/index/new-embedding-models-and-api-updates/) : Updates regarding OpenAI's embedding models that are crucial for understanding text and code embeddings.
- [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/) : Stanford's GloVe project, which provides a model for generating word embeddings that are useful for various NLP tasks.
- [Pearson Correlation Coefficient](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient) : Wikipedia article explaining the Pearson correlation coefficient and its relationship to cosine similarity.
- [OpenAI's Text and Code Embeddings by Contrastive Pre-Training](https://cdn.openai.com/papers/Text_and_Code_Embeddings_by_Contrastive_Pre_Training.pdf) : Research paper on contrastive pre-training for creating embeddings for text and code.
- [Colab Notebooks on Tensor Operations](https://colab.research.google.com/github/stared/thinking-in-tensors-writing-in-pytorch/blob/master/rnns/Word%20vectors.ipynb) : A Google Colab notebook illustrating the use of RNNs and word vectors in PyTorch.

## Topics

![](topics/Concept/Cosine%20Similarity)

![](topics/Concept/Embeddings)

![](topics/Concept/Transfer%20Learning)

![](topics/Concept/Self%20Supervised%20Learning)

![](topics/Concept/Task%20Specific%20Embeddings)