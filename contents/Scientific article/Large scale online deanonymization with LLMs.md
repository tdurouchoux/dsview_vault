---
already_read: false
link: https://arxiv.org/pdf/2602.16800
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
type: Content
upload_date: '2026-04-15'
---

https://arxiv.org/pdf/2602.16800
## Summary

LLMs enable scalable deanonymization of pseudonymous online accounts by extracting identity-relevant features from unstructured text, searching for matches via semantic embeddings, reasoning over top candidates, and calibrating confidence scores. The approach outperforms classical methods (e.g., Netflix Prize attack) across three settings: linking Hacker News to LinkedIn, matching Reddit users across communities, and linking temporally split Reddit profiles. Key findings include: (1) LLM agents autonomously re-identify users at 25–67% recall with 70–90% precision, (2) LLM-based pipelines achieve up to 68% recall at 90% precision (vs. near 0% for classical methods), and (3) performance scales robustly to large candidate pools (e.g., 55% recall at 90% precision for 89k candidates). The work highlights that pseudonymous privacy is no longer guaranteed, as LLMs reduce attack costs from hours of manual effort to minutes of automated processing. Ethical concerns include potential misuse for doxxing, surveillance, or targeted manipulation, though the authors argue publication is justified to raise awareness and enable defenses. Limitations include reliance on synthetic ground truth and the need for further research on mitigations like LLM guardrails or text anonymization.
## Links


## Topics

![[topics/Concept/Deanonymization]]

![[topics/Model/Gemini Embeddings]]

![[topics/Platform/Reddit]]

![[topics/Dataset/Anthropic Interviewer Dataset]]

![[topics/Tool/FAISS]]