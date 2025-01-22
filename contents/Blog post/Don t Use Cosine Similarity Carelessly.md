---
already_read: true
link: https://p.migdal.pl/blog/2025/01/dont-use-cosine-similarity?utm_campaign=Data_Elixir&utm_source=Data_Elixir_519
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Natural_Language_Processing
- Data_Quality
type: Content
upload_date: '2025-01-22'
---

https://p.migdal.pl/blog/2025/01/dont-use-cosine-similarity?utm_campaign=Data_Elixir&utm_source=Data_Elixir_519
## Summary

The article emphasizes caution when using cosine similarity in data science, particularly with vector embeddings. While embeddings can reveal relationships between items, blindly applying cosine similarity can lead to misleading results, such as matching questions to questions instead of questions to answers. 

Key points include:

- **Embeddings**: They transform raw data into vectors, allowing for the discovery of relationships. However, they can capture superficial similarities rather than meaningful ones.
- **Cosine Similarity**: A common method for comparing vectors, it calculates the cosine of the angle between them. While it has useful properties, its simplicity can be deceptive, and it may not always reflect true similarity.
- **Limitations**: Cosine similarity may not align with the training objectives of machine learning models, leading to unreliable results. It also compresses complex notions of similarity into a single metric, which can overlook nuanced perspectives.
- **Alternative Approaches**: Instead of relying solely on cosine similarity, the article suggests using large language models (LLMs) for more meaningful comparisons, fine-tuning embeddings for specific tasks, and employing prompt engineering to focus on relevant aspects of the data.
- **Best Practices**: To improve vector similarity, one should train custom embeddings, engineer prompts, and clean text before embedding.

Overall, the article advocates for a more intentional and nuanced approach to measuring similarity in data science.
## Links

1. [OpenAI Embedding Models and API Updates](https://openai.com/index/new-embedding-models-and-api-updates/) - Overview of the latest updates to OpenAI's embedding models and API, relevant for understanding modern embeddings.
2. [Stanford NLP GloVe](https://nlp.stanford.edu/projects/glove/) - Information on GloVe, a popular word embedding model that is often compared with other embedding techniques.
3. [Pearson Correlation Coefficient](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient) - A detailed explanation of Pearson correlation, which is related to cosine similarity and useful for understanding vector comparisons.
4. [Node2Vec](https://snap.stanford.edu/node2vec/) - A framework for learning continuous feature representations for nodes in networks, relevant for understanding embeddings in graph data.
5. [Text and Code Embeddings by Contrastive Pre-Training](https://cdn.openai.com/papers/Text_and_Code_Embeddings_by_Contrastive_Pre_Training.pdf) - A research paper discussing contrastive pre-training for embeddings, providing insights into advanced embedding techniques.
## Topics

![](topics/Concept/Cosine%20Similarity)

![](topics/Concept/Embeddings)

![](topics/Model/OpenAI%20text%20embedding%203%20large)

![](topics/Concept/Fine%20tuning)

![](topics/Concept/Transfer%20Learning)