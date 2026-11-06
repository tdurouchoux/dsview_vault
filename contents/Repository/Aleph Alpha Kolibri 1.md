---
already_read: true
link: https://huggingface.co/Aleph-Alpha/Kolibri-1
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2026-11-06'
---

https://huggingface.co/Aleph-Alpha/Kolibri-1

## Summary

Kolibri-1 is Aleph Alpha’s 78B-parameter Mixture-of-Experts (MoE) reasoning model optimized for German/English, long-context (up to 1M tokens), and efficient inference with tool calling and reasoning modes.

**Model Overview**
- Architecture: 50-layer MoE with 384 experts per layer, 6 routed + 1 shared expert per token.
- Parameters: 78B total, 3.46B active per token.
- Context: Native 262,144 tokens, validated up to 1,048,576 tokens.
- Precision: FP8 weights (128×128 blocks), BF16 for embeddings/LM head/norms/router.
- Languages: German (23.9% of training data) and English, with a German-optimized tokenizer (UniBPE).
- Hardware: ~78GB memory; min 2×A100 80GB or 1×H200/B200, recommended 2×H100 or B200/300.

**Key Features**
- Reasoning modes: Configurable effort levels (none/low/medium/high).
- Tool calling: Hermes-style, supports auto-tool choice and structured outputs.
- Long-context: Sliding-window attention (512 tokens) + full attention layers for efficiency.
- Training: Pre-trained on 20T tokens, mid-trained on 3.44T, long-context on 201B tokens.
- Data: Bilingual corpus (62.5% English, 23.9% German, 13.6% code), OCR’d PDFs (33% of long-context mix).

**Performance Highlights**
- Top scores in German/English benchmarks (e.g., GPQA Diamond DE: 81.3, EN: 84.3).
- Strong in math (AIME 2026 EN: 96.0), agentic tasks (BFCL v4 overall: 61.4), and code (SWE-Bench Verified: 66.4).
- Outperforms dense models (e.g., 70B) with fewer active parameters.

**Deployment**
- Libraries: Native support in Transformers (≥5.20) and vLLM (≥0.33.0).
- Serving: OpenAI-compatible API via vLLM/SGLang; Docker Model Runner.
- Hardware: Optimized for NVIDIA B200/H200 or A100 80GB.

**Training Details**
- Optimizers: Muon (2D backbone) + AdamW (others), learning rate 0.001.
- Quantization: FP8 KV cache, dynamic activation quantization.
- Energy: ~950 MWh (pre-/mid-/long-context training).

**Responsible Use**
- License: Apache 2.0 (weights only).
- Risks: Outdated knowledge (cutoff: June 2026), systemic biases, political bias mitigation.
- Guardrails: PII redaction, harmful content filtering, safety-focused SFT/RL.

## Links

- [Kolibri Technical Report](https://aleph-alpha.com/downloads/tech-report.pdf) : A detailed technical report on the Kolibri-1 model, covering its architecture, training methodology, evaluation results, and design goals.
- [Kolibri Data Summary (EU Template)](https://aleph-alpha.com/downloads/data-summary.pdf) : A summary of the training data used for Kolibri-1, formatted according to the European Commission's template for transparency.
- [EU AI Code of Practice](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai) : Official documentation of the EU General-Purpose AI Code of Practice, which Aleph Alpha adheres to with Kolibri-1.
- [vLLM Documentation for Kolibri-1 Integration](https://github.com/vllm-project/vllm/pull/60827) : GitHub pull request detailing vLLM's native support for the Kolibri-1 model, including setup and usage instructions.
- [Aleph Alpha Inference GitHub Repository](https://github.com/Aleph-Alpha/aleph-alpha-inference) : GitHub repository providing tools and libraries for deploying and interacting with Aleph Alpha models, including Kolibri-1.


## Topics

![[topics/Model/Kolibri 1]]

![[topics/Concept/Mixture of Experts MoE]]

![[topics/Dataset/RULER]]

![[topics/Dataset/HELMET]]

![[topics/Concept/Reasoning Effort]]

![[topics/Concept/Tool Calling]]

![[topics/Library/Transformers]]

![[topics/Library/vLLM]]

![[topics/Tool/SGLang]]

![[topics/Platform/Hugging Face]]