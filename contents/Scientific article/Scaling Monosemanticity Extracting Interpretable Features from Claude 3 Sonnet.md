---
already_read: false
link: https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- Natural_Language_Processing
- AI_regulation
type: Content
upload_date: '2024-05-29'
---

https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html
## Summary

The paper "Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet" by Anthropic researchers presents a method for extracting interpretable features from large language models using sparse autoencoders. The key findings and technical points are as follows:

1. **Scaling Dictionary Learning**: The researchers successfully scaled sparse autoencoders to Claude 3 Sonnet, a medium-sized production model, demonstrating that high-quality features can be extracted from large models. They trained three sparse autoencoders of varying sizes (1M, 4M, and 34M features) and found that the larger the autoencoder, the more features it could learn, with the 34M feature run achieving the lowest training loss.

2. **Feature Interpretability**: The paper provides evidence that the extracted features are interpretable and explain model behavior. The researchers demonstrated that features can be used to steer model outputs in specific, interpretable ways, such as modifying the model's demeanor, preferences, stated goals, and biases.

3. **Feature Survey**: The researchers found a diversity of highly abstract features in Claude 3 Sonnet, including features for famous people, countries and cities, type signatures in code, and more. They also identified features related to safety concerns, such as security vulnerabilities, bias, lying, deception, power-seeking, sycophancy, and dangerous or criminal content.

4. **Features as Computational Intermediates**: The paper shows that features can be used to examine the intermediate computation that the model uses to produce an output. The researchers demonstrated this by identifying features that correspond to specific steps in the model's reasoning process.

5. **Searching for Specific Features**: The researchers developed methods to search for features of particular interest, such as those that may be relevant for safety. They used single prompts, prompt combinations, geometric methods, and attribution to identify features related to safety concerns.

6. **Safety-Relevant Features**: The paper identifies several safety-relevant features, including features related to unsafe code, bias, sycophancy, deception, power-seeking, and dangerous or criminal content. The researchers caution that the existence of these features does not imply that the model is dangerous, but rather that they may be useful for analyzing and ensuring the safety of models.

7. **Comparison to Other Approaches**: The paper compares dictionary learning to other methods for identifying meaningful directions in model activation space, such as linear probes and activation steering. The researchers found that dictionary learning offers some advantages, such as being a one-time cost that produces millions of features, and allowing for the discovery of abstractions or associations formed by the model that may not have been predicted in advance.

8. **Limitations and Open Problems**: The paper acknowledges several limitations and open problems, including the need for more efficient algorithms to scale dictionary learning to larger models, the challenge of cross-layer superposition, and the need for a better understanding of the relationship between features and model behavior.

In summary, the paper presents a method for extracting interpretable features from large language models and demonstrates that these features can be used to understand and steer model behavior. The researchers also identify several safety-relevant features and discuss the potential implications for model safety.
## Links

- [Anthropic Core Views on AI Safety](https://www.anthropic.com/news/core-views-on-ai-safety) : Anthropic's core views on AI safety, providing insights into their approach to ensuring the safety of AI systems.
- [Neel Nanda's Guide to Mechanistic Interpretability](https://www.neelnanda.io/mechanistic-interpretability/getting-started) : A guide to mechanistic interpretability, offering an introduction to the field and its key concepts.

## Topics

![](topics/Concept/Monosemanticity)

![](topics/Tool/Sparse%20Autoencoders%20SAEs)

![](topics/Concept/Linear%20Representation%20Hypothesis)

![](topics/Concept/Dictionary%20Learning)

![](topics/Concept/Scaling%20Laws)

![](topics/Concept/Feature%20Interpretability)

![](topics/Concept/Feature%20Steering)

![](topics/Concept/Safety%20Relevant%20Features)