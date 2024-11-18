---
already_read: false
link: https://arxiv.org/pdf/1706.03762.pdf
read_priority: 1
source: null
tags:
- Natural_Language_Processing
- Deep_Learning
type: Content
upload_date: '2023-01-19'
---

![](artefacts/1706.03762.pdf)
## Summary

The paper introduces the Transformer, a novel architecture for sequence transduction that relies entirely on attention mechanisms, eliminating the need for recurrent or convolutional layers. Key points include:

- **Architecture**: The Transformer consists of an encoder-decoder structure with stacked self-attention and feed-forward layers. The encoder has six identical layers, each with multi-head self-attention and a feed-forward network. The decoder includes an additional attention layer to connect to the encoder's output.

- **Attention Mechanism**: The model employs scaled dot-product attention and multi-head attention, allowing it to focus on different parts of the input sequence simultaneously. This enhances the model's ability to capture long-range dependencies.

- **Positional Encoding**: Since the model lacks recurrence, positional encodings are added to input embeddings to retain information about the order of tokens.

- **Training Efficiency**: The Transformer achieves state-of-the-art results in machine translation tasks (WMT 2014 English-to-German and English-to-French) with significantly reduced training time compared to previous models, demonstrating superior performance with a BLEU score of 28.4 for English-to-German and 41.8 for English-to-French.

- **Generalization**: The Transformer also generalizes well to other tasks, such as English constituency parsing, achieving competitive results without task-specific tuning.

- **Training Details**: The model was trained on large datasets using the Adam optimizer, with techniques like label smoothing and dropout for regularization.

Overall, the Transformer architecture represents a significant advancement in the field of natural language processing, particularly in tasks requiring sequence transduction.
## Topics

![](topics/Model/Transformer)

![](topics/Concept/Self%20attention)

![](topics/Concept/Multi%20Head%20Attention)

![](topics/Dataset/WMT%202014%20English%20German)

![](topics/Dataset/WMT%202014%20English%20French)