---
already_read: true
link: https://blog.google/innovation-and-ai/technology/developers-tools/functiongemma/
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2026-01-15'
---

https://blog.google/innovation-and-ai/technology/developers-tools/functiongemma/
## Summary

Google has released FunctionGemma, a specialized version of their Gemma 3 270M model, fine-tuned for function calling. This model is designed to enable developers to create custom, fast, private, and local agents that can translate natural language into executable API actions. Key features include:

- **Unified Action and Chat**: FunctionGemma can generate structured function calls to execute tools and then switch context to summarize results in natural language.
- **Built for Customization**: The model is designed to be fine-tuned for specific tasks, significantly improving reliability and accuracy.
- **Engineered for the Edge**: It is lightweight enough to run on edge devices like the NVIDIA Jetson Nano and mobile phones, ensuring low latency and high privacy.
- **Broad Ecosystem Support**: The model is supported by popular tools across the entire workflow, from fine-tuning to deployment.

FunctionGemma is ideal for applications with a defined API surface, those ready for fine-tuning, and systems prioritizing local-first deployment. It can act as an independent agent for private, offline tasks or as an intelligent traffic controller for larger connected systems. Developers can explore its capabilities through demos in the Google AI Edge Gallery app and access guides, datasets, and deployment tools to build their own specialized agents.
## Links

- [FunctionGemma Model on Hugging Face](https://huggingface.co/ggml-org/functiongemma-270m-it-GGUF) : Access the FunctionGemma 270M model on Hugging Face for fine-tuning and deployment.
- [FunctionGemma Collection on Hugging Face](https://huggingface.co/collections/google/functiongemma) : Explore the collection of FunctionGemma models and resources on Hugging Face.
- [FunctionGemma Model Card on Hugging Face](https://huggingface.co/google/functiongemma-270m-it) : View the model card for the FunctionGemma 270M model on Hugging Face, including details on its capabilities and usage.
- [FunctionGemma on Ollama](https://ollama.com/library/functiongemma) : Find the FunctionGemma model on Ollama for easy deployment and integration.
- [FunctionGemma Physics Playground](https://huggingface.co/spaces/webml-community/FunctionGemma-Physics-Playground) : Interactive demo showcasing FunctionGemma's capabilities in a physics simulation playground.

## Topics

![[topics/Model/FunctionGemma]]

![[topics/Concept/Edge Computing]]

![[topics/Concept/AI Agents]]

![[topics/Concept/Mobile Actions]]

![[topics/Concept/TinyGarden]]

![[topics/Concept/Function Calling]]

![[topics/Concept/Fine tuning]]