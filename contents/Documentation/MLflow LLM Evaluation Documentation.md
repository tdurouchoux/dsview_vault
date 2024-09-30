---
already_read: true
link: https://mlflow.org/docs/latest/llms/llm-evaluate/index.html
read_priority: 0
source: Aucune
tags:
- MlOps
type: Content
upload_date: '2024-09-30'
---

https://mlflow.org/docs/latest/llms/llm-evaluate/index.html
## Summary

MLflow LLM Evaluation provides tools for evaluating large language models (LLMs) in various applications, such as question answering and text summarization. Key components include:

1. **Model Evaluation**: Supports MLflow pyfunc models, registered models, or any callable Python model. Evaluation requires metrics and evaluation data, which can be in various formats (e.g., pandas DataFrame).

2. **Evaluation Metrics**: Two types of metrics are available:
   - SaaS-based metrics (e.g., OpenAI) for scoring.
   - Function-based metrics for per-row evaluations (e.g., Rouge, Flesch Kincaid).

3. **Default and Custom Metrics**: Users can select default metrics for predefined model types or create custom metrics using the MLflow API.

4. **LLM-as-Judge Metrics**: MLflow includes pre-defined metrics that utilize LLMs to assess model outputs, such as answer similarity and relevance.

5. **Custom Metric Creation**: Users can create custom metrics using the `mlflow.metrics.genai.make_genai_metric()` function, which allows for detailed scoring criteria and examples.

6. **Evaluation Process**: Models can be evaluated directly using `mlflow.evaluate()`, which supports various input formats and allows for passing inference parameters.

7. **Viewing Results**: Evaluation results can be accessed programmatically or through the MLflow UI, where users can view aggregated metrics and per-row results.

Overall, MLflow LLM Evaluation streamlines the process of assessing LLM performance, making it easier for data scientists to implement and track evaluations in their workflows.
## Links

1. [OpenAI guide](https://platform.openai.com/account/api-keys) - Instructions on how to set up your OpenAI API key for accessing OpenAI services.
2. [ROUGE](https://huggingface.co/spaces/evaluate-metric/rouge) - A popular metric for evaluating text summarization models, useful for understanding model performance.
3. [precision_at_k](https://en.wikipedia.org/wiki/Evaluation_measures_(information_retrieval)#Precision_at_k) - Explanation of the precision at k metric, which is important for evaluating information retrieval systems.
4. [Databricks Foundation Models API](https://docs.databricks.com/en/machine-learning/model-serving/score-foundation-models.html) - Documentation on how to score foundation models using Databricks, relevant for deploying and evaluating models.
5. [this blog](https://www.databricks.com/blog/LLM-auto-eval-best-practices-RAG) - A blog post discussing best practices for evaluating large language models, providing insights into effective evaluation strategies.
## Topics

- [[topics/Library/MLflow and Metaflow]]
- [[topics/Concept/Model Evaluation]]
- [[topics/Concept/Prompt Engineering]]
- [[topics/Concept/Custom LLM-evaluation Metrics]]
- [[topics/Platform/MLflow AI Gateway]]