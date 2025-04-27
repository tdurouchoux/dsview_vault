---
already_read: true
link: https://mlflow.org/docs/latest/llms/llm-evaluate/index.html
read_priority: 0
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2024-09-30'
---

https://mlflow.org/docs/latest/llms/llm-evaluate/index.html
## Summary

MLflow provides functionality to evaluate Large Language Models (LLMs) through its `mlflow.evaluate()` API, which differs from traditional ML evaluations due to the lack of a single ground truth. Key components include:

1. **Model**: Can be an MLflow pyfunc model, a URI to a registered model, or any Python callable leading to a model.
2. **Metrics**: LLM evaluation metrics include heuristic-based metrics (like ROUGE and BLEU) and LLM-as-a-Judge metrics that evaluate model outputs using LLMs themselves to provide a nuanced assessment.

MLflow includes predefined metrics collections for various tasks, such as question answering and text summarization, alongside options to define custom metrics. The evaluation process involves preparing input data, which can be specified as various data structures including pandas DataFrames and lists.

For model evaluation:
- Models can be logged and referenced or directly evaluated via a callable function.
- The evaluation can be performed on static datasets, enabling the use of previous model outputs for assessments without re-running the models.

Results from evaluations can be accessed through code or viewed in the MLflow UI, including aggregated metrics and per-row evaluation results. The evaluation process supports additional inference parameters for more control over model interactions.

In summary, MLflow streamlines LLM evaluation by integrating sophisticated metrics and flexible input formats, allowing for detailed performance assessments that align more closely with human judgment.
## Links

- [MLflow GitHub Repository](https://github.com/mlflow/mlflow) : The official GitHub repository for MLflow, providing source code and contribution guidelines.
- [MLflow Python API Documentation](https://mlflow.org/docs/latest/api_reference/python_api/index.html) : Comprehensive documentation for MLflow's Python API, detailing available functions and usage.
- [MLflow Metrics Documentation](https://mlflow.org/docs/latest/python_api/mlflow.metrics.html) : Information on how to use MLflow Metrics for evaluating model performance.
- [Flesch-Kincaid Readability Tests](https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests#Flesch%E2%80%93Kincaid_grade_level) : Wikipedia page describing the Flesch-Kincaid readability tests, commonly used in LLM evaluations.
- [ROUGE Metric Information](https://huggingface.co/spaces/evaluate-metric/rouge) : A space on Hugging Face describing the ROUGE evaluation metric, which is useful for text summarization tasks.

## Topics

![](topics/Library/MLflow)

![](topics/Tool/MLflow%20LLM%20Evaluation)

![](topics/Concept/LLM%20Evaluation%20Metrics)

![](topics/Tool/HuggingFace%20Pipelines)

![](topics/Concept/Prompt%20Engineering)

![](topics/Tool/OpenAI%20API)