---
already_read: false
link: https://cdn.openai.com/pdf/08b7dee4-8bc6-4955-a219-7793fb69090c/Technical_report__Research_Preview_of_gpt_oss_safeguard.pdf
read_priority: 4
relevance: 0
source: Data Points
tags:
- Large_Language_Model
- AI_regulation
type: Content
upload_date: '2025-11-20'
---

https://cdn.openai.com/pdf/08b7dee4-8bc6-4955-a219-7793fb69090c/Technical_report__Research_Preview_of_gpt_oss_safeguard.pdf
## Summary

The report evaluates the performance of two open-weight reasoning models, gpt-oss-safeguard-120b and gpt-oss-safeguard-20b, which are designed to classify content based on provided policies. These models are fine-tuned from the gpt-oss models and are available under the Apache 2.0 license. Key findings include:

1. **Safety Classification Performance**: The gpt-oss-safeguard models outperform their gpt-oss counterparts and other models like gpt-5-thinking in multi-policy accuracy. However, they underperform in some categories of the Production Benchmarks evaluation.

2. **Multilingual Performance**: The models perform at parity with gpt-oss models across various languages, as evaluated by the MMMLU test.

3. **Safety Challenges and Mitigations**:
   - **Disallowed Content**: The models generally perform on par with gpt-oss models in standard evaluations but show minor degradations in more challenging production benchmarks.
   - **Jailbreaks**: gpt-oss-safeguard-120b shows improved robustness, while gpt-oss-safeguard-20b underperforms compared to gpt-oss-20b.
   - **Instruction Hierarchy**: The models underperform their gpt-oss counterparts in adhering to instruction hierarchies.
   - **Hallucinations**: The models perform similarly to gpt-oss models in hallucination evaluations, with slight variations in accuracy and hallucination rates.
   - **Fairness and Bias**: Both gpt-oss-safeguard models outperform their gpt-oss counterparts in the BBQ evaluation, indicating better performance in handling ambiguous and disambiguated questions.

The report concludes that while the gpt-oss-safeguard models show promising capabilities in safety classification and multilingual performance, there are areas for improvement, particularly in handling complex safety scenarios and adhering to instruction hierarchies.
## Links


## Topics

![[topics/Model/gpt oss safeguard 120b]]

![[topics/Model/gpt oss safeguard 20b]]

![[topics/Model/gpt 5 thinking]]

![[topics/Concept/Chain of Thought]]

![[topics/Concept/Structured Output]]

![[topics/Concept/Instruction Hierarchy]]

![[topics/Concept/Hallucination in Language Models]]