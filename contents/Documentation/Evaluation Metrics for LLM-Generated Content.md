---
already_read: true
link: https://learn.microsoft.com/en-us/ai/playbook/technology-guidance/generative-ai/working-with-llms/evaluation/list-of-eval-metrics
read_priority: 1
source: Me
tags:
- Natural_Language_Processing
- Model_evaluation
type: Content
upload_date: '2024-10-29'
---

https://learn.microsoft.com/en-us/ai/playbook/technology-guidance/generative-ai/working-with-llms/evaluation/list-of-eval-metrics
## Summary

The content discusses various evaluation metrics for assessing the performance of LLM-generated content. It emphasizes the need for both manual and automatic evaluation methods, highlighting key qualities such as fluency, coherence, relevance, factual consistency, and fairness.

Key categories of metrics include:

1. **Reference-based Metrics**: These compare generated text to a human-annotated reference. Notable metrics include:
   - **BLEU**: Measures precision in machine translation and text generation.
   - **ROUGE**: Focuses on recall, particularly useful in summarization tasks.

2. **Text Similarity Metrics**: These assess the overlap of words or sequences between texts, including:
   - **Levenshtein Similarity Ratio**: Measures similarity based on edit distance.
   - **Semantic Similarity Metrics**: Use embeddings to evaluate meaning similarity, such as BERTScore.

3. **Reference-free Metrics**: These do not rely on ground truth and evaluate based on context. They include:
   - **Quality-based Metrics**: Assess the relevance of summaries.
   - **Entailment-based Metrics**: Determine if generated text is consistent with the source.

4. **LLM-based Evaluators**: These utilize LLMs to evaluate text quality, offering scalability and explainability. They can be prompt-based and assess various qualities of the text.

5. **Metrics for LLM-generated Code**: Focus on functional correctness, readability, maintainability, and efficiency.

6. **Retrieval-Augmented Generation (RAG) Metrics**: Evaluate the performance of retrieval and generation models, focusing on faithfulness, answer relevancy, context relevancy, and context recall.

The content also mentions implementations like Azure Machine Learning prompt flow and OpenAI Evals for evaluating LLMs. Overall, it highlights the evolving landscape of evaluation metrics in the context of LLMs and their applications.
## Links

1. [BLEU (Bilingual Evaluation Understudy)](https://aclanthology.org/P02-1040.pdf) - A widely used metric for evaluating the quality of machine-translated text, applicable to various text generation tasks.
2. [ROUGE (Recall-Oriented Understudy for Gisting Evaluation)](https://aclanthology.org/W04-1013.pdf) - A set of metrics for evaluating the quality of generated text, particularly in summarization tasks, focusing on recall.
3. [BERTScore](https://github.com/Tiiiger/bert_score) - A metric that uses contextualized embeddings to measure the similarity between two texts, providing insights into semantic similarity.
4. [MoverScore](http://tiny.cc/vsqtbz) - A metric that evaluates the quality of generated text by measuring the distance between word embeddings, focusing on semantic similarity.
5. [RAGAS](https://github.com/explodinggradients/ragas/blob/main/src/ragas/metrics/_faithfulness.py) - An evaluation framework for Retrieval-Augmented Generation pipelines, providing metrics for assessing the performance of retrieval and generation models.
## Topics

- [[topics/Concept/Evaluation Metrics for RAG Systems]]
- [[topics/Library/OpenAI Evaluation Framework]]
- [[topics/Platform/Azure Machine Learning]]
- [[topics/Concept/Text Evaluation Metrics]]
- [[topics/Concept/Text Evaluation Metrics]]