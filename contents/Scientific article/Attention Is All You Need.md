---
already_read: false
link: https://arxiv.org/pdf/1706.03762.pdf
read_priority: 1
relevance: 0
source: null
tags:
- Natural_Language_Processing
- Deep_Learning
type: Content
upload_date: '2023-01-19'
---

https://arxiv.org/pdf/1706.03762.pdf
## Summary

The paper "Attention Is All You Need" introduces the Transformer, a novel neural network architecture for sequence transduction tasks, such as machine translation. The Transformer relies solely on attention mechanisms, eliminating the need for recurrence and convolutions. Here are the key points and takeaways:

1. **Architecture**:
   - The Transformer consists of an encoder and a decoder, both composed of stacked layers.
   - Each layer in the encoder and decoder contains two sub-layers: a multi-head self-attention mechanism and a position-wise feed-forward network.
   - The decoder also includes an additional sub-layer that performs multi-head attention over the encoder's output.

2. **Attention Mechanisms**:
   - The Transformer uses scaled dot-product attention, which computes attention scores by scaling the dot products of queries and keys by the square root of the key dimension.
   - Multi-head attention allows the model to jointly attend to information from different representation subspaces at different positions.
   - The Transformer applies attention in three ways: encoder self-attention, decoder self-attention, and encoder-decoder attention.

3. **Positional Encoding**:
   - Since the Transformer does not use recurrence or convolution, positional encodings are added to the input embeddings to inject information about the relative or absolute position of the tokens in the sequence.
   - The paper uses sinusoidal functions of different frequencies for positional encodings.

4. **Training and Results**:
   - The Transformer achieves state-of-the-art results on machine translation tasks, outperforming previous models on the WMT 2014 English-to-German and English-to-French translation tasks.
   - The model is trained on large datasets and can be trained significantly faster than architectures based on recurrent or convolutional layers.
   - The Transformer also generalizes well to other tasks, such as English constituency parsing.

5. **Advantages**:
   - The Transformer allows for significantly more parallelization, making it more efficient to train.
   - It can capture long-range dependencies more effectively due to its attention mechanisms.
   - The model is more interpretable, as attention distributions can reveal the relationships between different parts of the input and output sequences.

6. **Limitations and Future Work**:
   - The paper suggests that self-attention could be restricted to considering only a neighborhood of size r in the input sequence to improve computational performance for very long sequences.
   - Future work includes extending the Transformer to problems involving input and output modalities other than text and investigating local, restricted attention mechanisms.

In summary, the Transformer is a powerful and efficient architecture for sequence transduction tasks, leveraging attention mechanisms to achieve state-of-the-art results and improve interpretability.
## Links


## Topics

![[topics/Model/Transformer)]]

![[topics/Concept/Self Attention)]]

![[topics/Concept/Multi Head Attention)]]

![[topics/Concept/Positional Encoding)]]