---
already_read: true
link: https://infinitefaculty.substack.com/p/memorization-vs-generalization-in
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Deep_Learning
type: Content
upload_date: '2026-04-04'
---

https://infinitefaculty.substack.com/p/memorization-vs-generalization-in
## Summary

The article explores the nuanced relationship between memorization and generalization in deep learning, challenging the classical tradeoff perspective. Key points include:

1. **Classical View**: Traditional learning theory suggests a fundamental tradeoff—models that memorize training data poorly generalize to unseen data, as captured by VC dimension bounds.

2. **Deep Learning Puzzle**: Empirical success of deep learning (e.g., ImageNet) revealed models can memorize random labels yet generalize well, defying classical expectations. This sparked research into implicit biases favoring simpler, generalizable functions.

3. **Implicit Biases**:
   - **Architectural**: Neural networks inherently favor simpler functions (e.g., random parameters are more likely to instantiate simpler functions).
   - **Optimization**: Gradient-based training prioritizes learning simpler structures first (e.g., linear patterns before nonlinear ones). The *Neural Race Reduction* theory posits that shared, generalizable solutions are learned faster due to consistent gradient updates.

4. **Memorization’s Role**:
   - **Benign Overfitting**: Memorization may not harm generalization, especially if it’s localized (e.g., rare exceptions or noisy labels).
   - **Supportive Memorization**: Memorizing specific examples (e.g., "celebrity" entities) can accelerate learning of generalizable structures.
   - **Episodic Recall**: Explicit memorization (e.g., storing veridical experiences) may enable flexible reuse of information for novel tasks.

5. **Language Models (LMs)**:
   - Despite criticisms of LMs as "stochastic parrots," evidence shows they learn generalizable structures (e.g., syntax, algorithms) alongside memorization.
   - Benign overfitting and organized representations suggest memorization doesn’t always hinder generalization.

6. **Open Questions**:
   - Simplicity ≠ always better generalization (complexity can interact with architecture/objectives).
   - Emerging theories (e.g., compression-based capacity measures) aim to reconcile theory with deep learning’s empirics but remain incomplete.

**Takeaway**: Memorization and generalization are not inherently opposed; implicit biases in architecture and optimization, along with benign forms of memorization, enable deep learning models to generalize effectively despite memorizing training data.
## Links

- [Implicit Bias in Deep Learning: A Survey of Generalization and Memorization](https://arxiv.org/abs/1906.11300) : This paper explores the implicit biases in deep learning models that favor simpler functions, which can lead to better generalization. It aligns with the discussion on architectural and optimization biases in the provided content.
- [The Neural Race Reduction: A Theoretical Framework for Learning Generalizable Structures](https://proceedings.mlr.press/v162/saxe22a.html) : This paper introduces the Neural Race Reduction framework, which explains why models tend to learn simpler, shared structures faster than idiosyncratic ones. It supports the optimization-based perspective on memorization and generalization discussed in the content.
- [Benign Overfitting: When Memorization Does Not Hurt Generalization](https://proceedings.mlr.press/v70/arpit17a) : This work demonstrates theoretical and empirical evidence for 'benign overfitting,' where models memorize training data without negatively impacting generalization performance. It directly relates to the content's discussion on memorization and generalization.
- [VC Dimension and Classical Learning Theory](https://en.wikipedia.org/wiki/Vapnik%E2%80%93Chervonenkis_dimension#In_statistical_learning_theory) : This Wikipedia page provides an overview of VC dimension, a fundamental concept in classical learning theory that captures the tradeoff between memorization capacity and generalization. It is referenced in the content to explain classical perspectives on overfitting and generalization.
- [Stochastic Parrots: The Dangers of Language Models Memorizing Training Data](https://www.newyorker.com/tech/annals-of-technology/chatgpt-is-a-blurry-jpeg-of-the-web) : This New Yorker article by Ted Chiang critiques language models as 'blurry JPEGs of the web,' emphasizing their reliance on memorization. It is relevant to the content's discussion on language models and their generalization capabilities.

## Topics

![[topics/Concept/Memorization vs Generalization]]

![[topics/Concept/Benign Overfitting]]

![[topics/Concept/Implicit Biases in Machine Learning]]

![[topics/Concept/Neural Race Reduction]]

![[topics/Concept/Architectural Biases in Neural Networks]]

![[topics/Concept/Optimization Biases]]

![[topics/Concept/Episodic Recall in Machine Learning]]