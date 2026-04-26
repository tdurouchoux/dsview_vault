---
already_read: false
link: https://arxiv.org/pdf/2301.08243
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Deep_Learning
type: Content
upload_date: '2026-04-26'
---

https://arxiv.org/pdf/2301.08243
## Summary

I-JEPA (Image-based Joint-Embedding Predictive Architecture) introduces a self-supervised learning method for images that avoids hand-crafted data augmentations by predicting representations of target blocks from a single context block. Key technical points include:

- **Core Idea**: Predict high-level semantic representations of masked image regions (target blocks) using a context block, leveraging Vision Transformers (ViT) for scalability.
- **Masking Strategy**: Uses multi-block masking with large, semantically meaningful target blocks and informative context blocks to guide learning.
- **Architecture**: Consists of a context encoder (ViT), target encoder (ViT with EMA updates), and a lightweight predictor (narrow ViT).
- **Loss Function**: L2 distance between predicted and target patch representations in embedding space, avoiding pixel-level reconstruction.
- **Efficiency**: Trains a ViT-Huge/14 on ImageNet in under 72 hours (16 A100 GPUs), outperforming methods like MAE and iBOT in compute efficiency.
- **Performance**: Achieves strong results in linear probing, semi-supervised learning, and transfer tasks (e.g., object counting, depth prediction), while being competitive with view-invariant methods.
- **Key Design Choices**: Predicting in representation space (not pixel space) and masking the output of the target encoder (not input) are critical for semantic learning.
- **Scalability**: Benefits from larger models and datasets, with improved performance on diverse downstream tasks.

The paper contrasts I-JEPA with invariance-based (e.g., SimCLR, DINO) and generative (e.g., MAE, BEiT) self-supervised methods, highlighting its efficiency and semantic representation quality without relying on augmentations.
## Links


## Topics

![[topics/Concept/Self Supervised Learning]]

![[topics/Concept/Joint Embedding Predictive Architecture JEPA]]

![[topics/Model/Vision Transformer ViT]]

![[topics/Concept/Masked Autoencoders MAE]]

![[topics/Concept/Representation Collapse]]

![[topics/Concept/Energy Based Models EBMs]]

![[topics/Concept/Non Parametric Instance Discrimination]]

![[topics/Concept/Predictive Coding]]

![[topics/Concept/Contrastive Learning]]