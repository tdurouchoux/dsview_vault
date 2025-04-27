---
already_read: false
link: https://jiachenzhu.github.io/DyT/
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Deep_Learning
- Natural_Language_Processing
- Computer_Vision
type: Content
upload_date: '2025-03-17'
---

https://jiachenzhu.github.io/DyT/
## Summary

This paper presents the Dynamic Tanh (DyT) layer as an effective alternative to traditional normalization layers (like Layer Norm or RMSNorm) in Transformer architectures. The authors argue that Transformers without normalization can perform as well or better, often without extensive hyperparameter tuning. DyT operates as a simple element-wise transformation, $$\mathrm{DyT}(\boldsymbol{x}) = \tanh(\alpha \boldsymbol{x})$$, and is founded on the observation that normalization layers produce S-shaped tanh-like mappings for inputs.

Key findings include:
- Layer normalization functions similarly to scaled tanh functions, with earlier layers exhibiting linear behavior and deeper layers showing distinct S-shaped output curves.
- Extensive evaluations across various tasks and models (including supervised and self-supervised learning in vision, language, and speech) demonstrate DyT's robustness, matching or exceeding the performance of normalized models.

The implementation of DyT in PyTorch is summarized in a straightforward code snippet. The research provides new insights into the necessity of normalization layers in neural networks, questioning their role in achieving performance in deep learning models.
## Links

- [Transformers without Normalization - Paper](https://arxiv.org/abs/2503.10622) : The research paper detailing the findings and methodology of the Transformers without normalization using Dynamic Tanh.
- [DyT Code Repository](https://github.com/jiachenzhu/DyT) : The GitHub repository containing implementation details for the Dynamic Tanh (DyT) layer in PyTorch.
- [Kaiming He's Professional Page](https://people.csail.mit.edu/kaiming/) : Kaiming He's professional profile, providing information on his research and contributions to computer vision and deep learning.
- [Yann LeCun's Professional Page](http://yann.lecun.com) : Yann LeCun's personal page showcasing his research, publications, and insights in machine learning and AI.
- [Zhuang Liu's Personal Website](https://liuzhuang13.github.io) : Zhuang Liu's personal website with resources and information on his work in artificial intelligence and deep learning.

## Topics

![](topics/Concept/Dynamic%20Tanh%20DyT)

![](topics/Concept/Normalization%20Techniques%20in%20Neural%20Networks)

![](topics/Library/PyTorch)

![](topics/Model/Vision%20Transformer%20ViT)

![](topics/Model/wav2vec%202%200)

![](topics/Model/Diffusion%20Models)