---
already_read: true
link: https://learn.microsoft.com/en-us/ai/playbook/technology-guidance/generative-ai/working-with-llms/evaluation/list-of-eval-metrics
read_priority: 1
relevance: 0
source: Me
tags:
- Large_Language_Model
type: Content
upload_date: '2024-10-29'
---

https://learn.microsoft.com/en-us/ai/playbook/technology-guidance/generative-ai/working-with-llms/evaluation/list-of-eval-metrics
## Summary

The content discusses various evaluation metrics used to assess the performance of large language model (LLM)-generated text. Evaluation methods are categorized into manual and automatic approaches, with a focus on automatic methods that measure key qualities like fluency, coherence, relevance, factual consistency, and fairness.

1. **Reference-based Metrics**: These metrics compare generated text to a human-annotated reference. Key examples include:
   - **BLEU**: Calculates precision based on n-grams in machine translation, often used in paraphrase and summarization tasks. 
   - **ROUGE**: Measures recall for generated text, especially useful in summarization through ROUGE-N (n-grams) and ROUGE-L (longest common subsequence).

2. **Text Similarity Metrics**: These metrics assess the overlap of words between texts. The **Levenshtein Similarity Ratio** measures similarity by calculating the minimum edits required to transform one string into another.

3. **Semantic Similarity Metrics**: Utilize contextualized embeddings to determine how closely related the meanings of two texts are, employing cosine similarity.

4. **Reference-free Metrics**: These metrics assess text quality without relying on references. They include quality-based assessments (like SUPERT) and entailment-based metrics (like SummaC) to check consistency and factual accuracy.

5. **LLM-based Evaluators**: These models assess generated text’s quality using internal prompts, with methods like Reason-then-Score and Multiple Choice Question Scoring. Challenges include positional bias and reliability.

6. **Metrics for Code Generation**: Functional correctness evaluates how well generated code performs against specified inputs and expected outputs. Rule-based metrics can also assess syntax correctness, format consistency, and keyword presence.

7. **Automatic Test Generation**: Involves generating various test cases for evaluation, allowing LLMs to showcase performance across different contexts.

8. **Metrics for Retrieval-Augmented Generation (RAG)**: Metrics like faithfulness and context relevancy evaluate how well generated responses correspond with context and the quality of information retrieved.

The document includes implementations like Azure Machine Learning prompt flow for classification metrics and OpenAI Evals for LLM evaluation benchmarks. Overall, it highlights a comprehensive framework for evaluating LLM-generated content across multiple dimensions.
## Links

- [Large Language Models: Are State-of-the-Art Evaluators of Translation Quality](https://www.researchgate.net/publication/368879719_Large_Language_Models_Are_State-of-the-Art_Evaluators_of_Translation_Quality) : This paper discusses how large language models can be utilized to assess translation quality, highlighting their capabilities as evaluators.
- [OpenAI Evals: Evaluation Framework for LLMs](https://github.com/openai/evals) : A framework for evaluating LLMs and LLM systems, this repository contains benchmarks and tools for assessment.
- [BERTScore: A Method for Evaluating Text Generation](https://github.com/Tiiiger/bert_score) : BERTScore is a metric that utilizes contextual embeddings for evaluating the similarity between generated and reference texts.
- [RAGAS: An Evaluation Framework for Retrieval-Augmented Generation](https://github.com/explodinggradients/ragas/blob/main/src/ragas/metrics/_faithfulness.py) : RAGAS provides metrics specifically tailored for assessing Retrieval-Augmented Generation pipelines.
- [A Survey on Evaluation Metrics for Text Generation](http://arxiv.org/abs/1910.12840) : This survey focuses on various metrics for evaluating text generation tasks, providing insights on their effectiveness and application.

## Topics

![](topics/Concept/Evaluation%20Metrics%20for%20Text%20Generation)

![](topics/Concept/Text%20Similarity%20Metrics)

![](topics/Concept/Prompt%20Engineering)

![](topics/Concept/LLM%20based%20Evaluation%20Techniques)

![](topics/Concept/Automatic%20Test%20Generation)