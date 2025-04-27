---
already_read: false
link: https://arxiv.org/pdf/1706.03762.pdf
read_priority: 1
relevance: 0
source: null
tags:
- Natural_Language_Processing
- Deep_Learning
- Model_evaluation
type: Content
upload_date: '2023-01-19'
---

![](artefacts/1706.03762.pdf)
## Summary

The paper introduces the Transformer, a novel architecture for sequence transduction tasks that relies entirely on attention mechanisms, eliminating the need for recurrence or convolutions typically found in previous models. The authors demonstrate that the Transformer provides superior performance in machine translation tasks, achieving state-of-the-art BLEU scores on both the WMT 2014 English-to-German and English-to-French datasets. Key features of the Transformer include:

1. **Model Architecture**: Consists of multi-head self-attention and feed-forward networks for both encoder and decoder stacks, allowing for enhanced parallelization.
  
2. **Self-Attention Mechanism**: Computes dependencies globally across sequences without prior position alignment, which facilitates the learning of long-range dependencies.

3. **Multi-Head Attention**: Divides the attention computation into multiple sub-spaces, allowing the model to learn different representations simultaneously.

4. **Positional Encoding**: Injects information about the position of tokens using sine and cosine functions to maintain the order of input sequences.

5. **Training Efficiency**: Achieves high quality translation while requiring significantly less training time, being capable of training in under 12 hours with 8 GPUs.

6. **Generalization**: The model demonstrates strong performance on other tasks, such as English constituency parsing, establishing benchmarks competitive with state-of-the-art results.

Results showcase the effectiveness of the Transformer compared to other architectures, underscoring its potential for various applications in natural language processing. The paper concludes with the aspiration for extending this attention-based model to different modalities and improving generation efficiency.
## Topics

![](topics/Model/Transformer)

![](topics/Concept/Self%20Attention)

![](topics/Concept/Multi%20Head%20Attention)

![](topics/Dataset/WMT%202014%20English%20German%20Translation%20Dataset)

![](topics/Concept/Positional%20Encoding)

![](topics/Library/Tensor2Tensor)