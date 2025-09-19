---
already_read: true
link: https://huggingface.co/blog/jupyter-agent-2
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2025-09-19'
---

https://huggingface.co/blog/jupyter-agent-2
## Summary

The article discusses the development of Jupyter Agents, which are designed to enhance the capabilities of large language models (LLMs) by enabling them to execute code directly within Jupyter notebooks. The goal is to create more autonomous and capable agents for data analysis and data science tasks.

Key points include:

1. **DABStep Benchmark**: Introduced to evaluate data science agents on realistic tasks, with current models struggling to achieve high accuracy.

2. **First Baseline**: Initial results with Qwen3-4B-Thinking-2507 showed modest performance, indicating room for improvement.

3. **Scaffolding**: Simplified scaffolding around the model improved performance significantly, with a focus on reducing dependencies and aligning with the model's capabilities.

4. **Training Pipeline**: Involves generating high-quality training data from Kaggle notebooks, including steps like deduplication, dataset downloading, educational scoring, and QA generation.

5. **Dataset Pipeline**: A multi-stage process to clean and prepare Kaggle notebooks, ensuring high-quality, relevant data for training.

6. **Results**: Fine-tuning Qwen3-4B with the generated dataset showed notable improvements in performance on the DABStep benchmark, demonstrating the potential of small models when paired with the right data and scaffolding.

7. **Next Steps**: Future directions include generating more challenging questions, scaling up training data, exploring knowledge distillation, and building an RL environment for further improvements.

The article concludes by encouraging the community to experiment with the provided dataset and codebase to continue advancing the capabilities of Jupyter Agents.
## Links

- [Jupyter Agent Dataset](https://huggingface.co/datasets/jupyter-agent/jupyter-agent-dataset) : Dataset used for training and evaluating the Jupyter Agent model.
- [Qwen3-4B-Thinking-2507](https://huggingface.co/Qwen/Qwen3-4B-Thinking-2507) : Model used for generating synthetic QA pairs and traces for the Jupyter Agent dataset.
- [Qwen3-Coder-480B-A35B-Instruct](https://huggingface.co/Qwen/Qwen3-Coder-480B-A35B-Instruct) : Model used for generating synthetic QA pairs and traces for the Jupyter Agent dataset.

## Topics

![[topics/Tool/Jupyter Agent]]

![[topics/Tool/Smolagents]]

![[topics/Library/DataTrove]]

![[topics/Tool/KaggleHub]]

![[topics/Tool/TRL]]

![[topics/Dataset/Kaggle Notebooks Dataset]]

![[topics/Dataset/Kaggle Datasets]]

![[topics/Dataset/Jupyter Agent Dataset]]

![[topics/Model/Qwen 3 Coder]]

![[topics/Platform/E2B]]