---
already_read: true
link: https://learn.microsoft.com/en-us/ai/playbook/technology-guidance/generative-ai/working-with-llms/evaluation/list-of-eval-metrics
read_priority: 1
relevance: 0
source: Me
tags:
- Large_Language_Model
- Model_evaluation
type: Content
upload_date: '2024-10-29'
---

https://learn.microsoft.com/en-us/ai/playbook/technology-guidance/generative-ai/working-with-llms/evaluation/list-of-eval-metrics
## Summary

The article discusses various evaluation metrics for Large Language Model (LLM)-generated content, categorizing them into reference-based, reference-free, and LLM-based evaluators.

**Reference-based Metrics:**
- **N-gram based metrics:** BLEU (precision-based), ROUGE (recall-based) evaluate similarity between generated and reference text using n-grams.
- **Text Similarity metrics:** Levenshtein Similarity Ratio and its variants measure similarity based on string edits.
- **Semantic Similarity metrics:** BERTScore, MoverScore, and SMS use contextualized embeddings to measure similarity, but may have limitations like poor correlation with human evaluators.

**Reference-free Metrics:**
- **Quality-based metrics:** SUPERT, BLANC, ROUGE-C evaluate summary quality without references.
- **Entailment-based metrics:** SummaC, FactCC, DAE detect factual inconsistencies using Natural Language Inference.
- **Factuality, QA, and QG-based metrics:** SRLScore, QAFactEval, QuestEval measure factual consistency and relevance.

**LLM-based Evaluators:**
- **Prompt-based evaluators:** LLMs can evaluate text based on prompts, with frameworks like RTS, MCQ, H2H, and G-Eval. Challenges include positional bias, verbosity bias, and self-enhancement bias.
- **LLM embedding-based metrics:** Use embeddings from LLMs to calculate semantic similarity.

**Metrics for LLM-generated code:**
- **Functional Correctness:** Evaluates if generated code produces desired output.
- **Rule-based Metrics:** Syntax correctness, format check, language check, keyword presence.
- **Automatic Test Generation:** LLMs generate test cases for evaluation.

**Metrics for RAG pattern:**
- **Generation-related metrics:** Faithfulness, Answer Relevancy.
- **Retrieval-related metrics:** Context Relevancy, Context Recall.

The article also mentions implementations like Azure Machine Learning prompt flow, OpenAI Evals, and RAGAS for evaluating LLMs.
## Links

- [BERTScore GitHub Repository](https://github.com/Tiiiger/bert_score) : GitHub repository for BERTScore, a metric for evaluating the performance of text generation models using BERT embeddings.
- [OpenAI Evals](https://github.com/openai/evals) : An open-source framework for evaluating large language models (LLMs) and an open-source registry of benchmarks.
- [RAGAS Faithfulness Metric](https://github.com/explodinggradients/ragas/blob/main/src/ragas/metrics/_faithfulness.py) : GitHub repository for the RAGAS framework, specifically the faithfulness metric used to evaluate the factual consistency of generated answers against given context.

## Topics

![[topics/Concept/Rule based Metrics]]

![[topics/Concept/Reference free Metrics]]

![[topics/Concept/Levenshtein Similarity Ratio]]

![[topics/Concept/Reference based Metrics]]

![[topics/Concept/Semantic Similarity Metrics]]

![[topics/Concept/Evaluation Metrics]]

![[topics/Concept/ROUGE]]

![[topics/Concept/LLM based Evaluators]]

![[topics/Concept/Functional Correctness]]

![[topics/Concept/BLEU Score]]