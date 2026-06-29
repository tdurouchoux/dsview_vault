---
already_read: true
link: https://github.com/kubeai-project/kubeai
read_priority: 0
relevance: 4
source: null
tags:
- Cloud_Computing
type: Content
upload_date: '2026-06-29'
---

https://github.com/kubeai-project/kubeai
## Summary

KubeAI is a Kubernetes operator for deploying and scaling ML models in production, supporting LLMs (vLLM, Ollama), embeddings (Infinity), speech-to-text (FasterWhisper), and reranking. Key features include intelligent scaling (zero-to-n), optimized routing for vLLM’s KV cache, model caching, dynamic LoRA adapters, and event streaming (Kafka/PubSub). It offers OpenAI-compatible APIs, avoids dependencies like Istio/Knative, and runs on CPU/GPU/TPU. Architecture includes a model proxy (load balancing, queueing) and operator (model management). Predefined models and Helm charts simplify deployment. Adopted by companies like Google Cloud, Lambda, and Arcee. Quickstart involves local Kubernetes clusters (kind/minikube) and Helm installation.
## Links

- [KubeAI Official Documentation](https://www.kubeai.org) : The official documentation for KubeAI, providing detailed guides, API references, and conceptual explanations for deploying and managing AI models on Kubernetes.
- [Telescope AI Platform](https://trytelescope.ai) : A platform that uses KubeAI for multi-region, large-scale batch LLM inference, highlighting its adoption in production environments.
- [Lambda AI Developer Cloud](https://lambdalabs.com) : Lambda's AI cloud platform, which supports KubeAI for running inference workloads, including a tutorial and video demonstration.
- [Vultr Managed Kubernetes](https://www.vultr.com) : Vultr's managed Kubernetes service, which supports deploying KubeAI for GPU inference workloads.
- [Arcee AI Platform](https://www.arcee.ai) : A platform that leverages KubeAI for multi-region, multi-tenant small language model (SLM) inference, showcasing its scalability and flexibility.

## Topics

![[topics/Platform/Kubernetes]]

![[topics/Tool/FasterWhisper]]

![[topics/Tool/Infinity]]

![[topics/Concept/LoRA Low Rank Adaptation]]

![[topics/Concept/Model Caching]]

![[topics/Concept/Prefix Aware Load Balancing]]

![[topics/Concept/Scale from Zero]]

![[topics/Concept/OpenAI Compatible API]]

![[topics/Library/vLLM]]

![[topics/Tool/Ollama]]