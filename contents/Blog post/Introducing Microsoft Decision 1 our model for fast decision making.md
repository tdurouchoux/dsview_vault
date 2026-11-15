---
already_read: true
link: https://commandline.microsoft.com/microsoft-decision-1-model-foundry/
read_priority: 0
relevance: 3
source: Data Points
tags:
- Large_Language_Model
type: Content
upload_date: '2026-11-15'
---

https://commandline.microsoft.com/microsoft-decision-1-model-foundry/

## Summary

Microsoft-Decision-1 is a new decision-scoring model optimized for low-latency, high-quality structured decision tasks, outperforming LLMs and other decision models in speed and accuracy.

**Performance**
- Outperforms LLMs and other decision models in latency and quality for structured tasks.
- Highest accuracy in a 36-benchmark comparison (~150,000 questions, blinded from training).
- 2.5x faster than H2O-Lightning-4B v1.1 and 35x faster than GPT-6 Sol.
- P50 latency ~35x faster than GPT-6 Sol.

**Capabilities**
- Supports yes/no, multiple-choice, rating, rubric-based grading, and agent action evaluation.
- Structured API for calibrated probability scores per option.
- Handles routing, classification, prioritization, verification, and workflow control.

**Key Features**
- Generalizes across 36+ benchmarks (routing, ranking, multilingual, safety, etc.).
- Robust to input perturbations (1.3% decision flip rate; 0% on paraphrased/reordered options).
- Well-calibrated confidence scores (90% prediction ≈ 90% accuracy).
- Strong safety performance (5,250 requests tested; blocks harmful content without over-filtering).

**Use Cases**
- 14x faster and 200x cheaper than GPT-6 Sol for XBOX feedback labeling (10K+ items).
- Competitive with GPT-5.6 Luna for Copilot quality control at 100x speed.
- 46x more consistent and 3x faster for adaptive scientific replanning.
- Applications: agent controls, model routing, data labeling, AI judging, incident response, etc.

**Availability**
- Accessible via Microsoft Foundry and OpenRouter.
- Pricing: $0.042 per million input tokens (output tokens free).
- Documentation: [Microsoft Learn](https://learn.microsoft.com/en-us/azure/foundry/foundry-models/how-to/use-foundry-models-microsoft-decision).

## Links

- [Microsoft-Decision-1 Model in Azure Foundry](https://ai.azure.com/catalog/models/Microsoft-Decision-1) : Official catalog page for Microsoft-Decision-1, a decision-scoring model designed for fast, structured decision-making tasks. This is the primary resource for developers to access the model.
- [Microsoft-Decision-1 on OpenRouter](https://openrouter.ai/microsoft/microsoft-decision-1) : OpenRouter integration page for Microsoft-Decision-1, providing an alternative platform for developers to use the model.
- [Microsoft-Decision-1 Documentation](https://learn.microsoft.com/en-us/azure/foundry/foundry-models/how-to/use-foundry-models-microsoft-decision) : Official documentation for Microsoft-Decision-1, including setup, API usage, and best practices for integrating the model into applications.
- [H2O-Lightning-4B Model on Hugging Face](https://huggingface.co/h2oai/h2o-lightning-4b) : Hugging Face repository for H2O-Lightning-4B, a benchmarked decision model referenced in the performance comparison of Microsoft-Decision-1.
- [Strands-Decider 2B GitHub Repository](https://github.com/strands-labs/strands-decider) : GitHub repository for Strands-Decider 2B, another benchmarked decision model mentioned in the performance comparison of Microsoft-Decision-1.


## Topics

![[topics/Model/Microsoft Decision 1]]

![[topics/Model/Qwen3]]

![[topics/Model/H2O Lightning 4B]]

![[topics/Model/GPT 5]]

![[topics/Platform/Microsoft Azure AI Foundry]]

![[topics/Concept/Decision models]]

![[topics/Dataset/JevBench]]

![[topics/Platform/OpenRouter]]