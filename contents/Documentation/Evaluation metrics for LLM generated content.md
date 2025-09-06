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

The article discusses various evaluation metrics for Large Language Model (LLM)-generated content, categorizing them into reference-based, reference-free, and LLM-based metrics.

**Reference-based Metrics:**
- **N-gram based metrics:** BLEU, ROUGE, and JS divergence measure similarity between generated text and reference text using n-grams.
  - **BLEU Score:** Evaluates machine-translated text quality by comparing candidate translations to reference translations.
  - **ROUGE:** Measures recall, focusing on the number of words the model can recall, useful for summarization tasks.
- **Text Similarity metrics:** Levenshtein Similarity Ratio measures the similarity between two sequences based on the minimum number of single-character edits required to change one string into the other.
- **Semantic Similarity metrics:** BERTScore, MoverScore, and Sentence Mover Similarity (SMS) use contextualized embeddings to measure the similarity between two texts.

**Reference-free Metrics:**
- **Quality-based metrics:** SUPERT and BLANC measure the similarity of a summary with a BERT-based pseudo-reference or the difference in accuracy of two reconstructions of masked-tokens.
- **Entailment-based metrics:** SummaC, FactCC, and DAE detect factual inconsistencies by determining whether the output text entails, contradicts, or undermines the premise.
- **Factuality, QA, and QG-based metrics:** SRLScore, QAFactEval, QuestEval evaluate whether generated text contains incorrect information and measure factual consistency and relevance.

**LLM-based Evaluators:**
- **Prompt-based evaluators:** Use LLMs to judge text quality based on fluency, coherence, consistency, and relevancy. Frameworks include Reason-then-Score (RTS), Multiple Choice Question Scoring (MCQ), Head-to-head scoring (H2H), and G-Eval.
- **LLM embedding-based metrics:** Use embedding models from LLMs to calculate semantic similarity.

**Metrics for LLM-generated code:**
- **Functional Correctness:** Evaluates the accuracy of NL-to-code generation tasks.
- **Rule-based Metrics:** Syntax correctness, format check, language check, and keyword presence.
- **Automatic Test Generation:** Uses LLMs to generate test cases and measure model performance.

**Metrics for RAG pattern:**
- **Generation-related metrics:** Faithfulness and Answer Relevancy.
- **Retrieval-related metrics:** Context Relevancy and Context Recall.

The article also mentions implementations like Azure Machine Learning prompt flow, OpenAI Evals, and RAGAS for evaluating LLMs and LLM systems.
## Links

- [BERTScore GitHub Repository](https://github.com/Tiiiger/bert_score) : GitHub repository for BERTScore, a metric that uses BERT embeddings to measure the semantic similarity between two texts.
- [RAGAS Faithfulness Metric Implementation](https://github.com/explodinggradients/ragas/blob/main/src/ragas/metrics/_faithfulness.py) : Implementation of the faithfulness metric from the RAGAS framework, which measures the factual consistency of generated answers against the given context.
- [OpenAI Evals Framework](https://github.com/openai/evals) : An open-source framework for evaluating large language models (LLMs) and an open-source registry of benchmarks.

## Topics

![](topics/Concept/Evaluation%20Metrics)

![](topics/Concept/BLEU%20Score)

![](topics/Concept/ROUGE)

![](topics/Concept/Levenshtein%20Similarity%20Ratio)

![](topics/Concept/Semantic%20Similarity)

![](topics/Concept/Reference%20free%20Metrics)

![](topics/Concept/LLM%20based%20Evaluators)

![](topics/Concept/Functional%20Correctness)

![](topics/Concept/Rule%20based%20Metrics)

![](topics/Concept/Automatic%20Test%20Generation)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)