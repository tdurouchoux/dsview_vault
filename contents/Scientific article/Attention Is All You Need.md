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

- **Architecture**: The Transformer consists of an encoder-decoder structure with stacked self-attention and feed-forward layers. The encoder has six identical layers, each with multi-head self-attention and a feed-forward network, while the decoder includes an additional attention layer to attend to the encoder's output.

- **Attention Mechanism**: The model employs scaled dot-product attention and multi-head attention, allowing it to focus on different parts of the input sequence simultaneously. This enhances the model's ability to capture long-range dependencies.

- **Positional Encoding**: Since the model lacks recurrence and convolution, it uses positional encodings to retain information about the order of tokens in the sequence.

- **Training Efficiency**: The Transformer achieves state-of-the-art results in machine translation tasks (WMT 2014 English-to-German and English-to-French) with significantly reduced training time compared to previous models, demonstrating superior performance with a BLEU score of 28.4 for English-to-German and 41.8 for English-to-French.

- **Generalization**: The Transformer also generalizes well to other tasks, such as English constituency parsing, achieving competitive results with fewer training examples.

- **Training Details**: The model was trained using the Adam optimizer with a learning rate schedule and regularization techniques like dropout and label smoothing.

Overall, the Transformer architecture represents a significant advancement in the field of natural language processing, particularly for tasks requiring sequence transduction.
## Topics

- [[topics/Library/Transformers with Reinforcement Learning]]
- [[topics/Concept/Self-Attention]]
- [[topics/Concept/Multi-Head Attention]]
- [[topics/Concept/Positional Encoding]]
- [[topics/Library/tensor2tensor]]