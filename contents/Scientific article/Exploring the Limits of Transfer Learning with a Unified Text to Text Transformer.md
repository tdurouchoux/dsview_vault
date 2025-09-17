---
already_read: false
link: https://arxiv.org/pdf/1910.10683
read_priority: 5
relevance: 0
source: null
tags:
- Natural_Language_Processing
- Deep_Learning
type: Content
upload_date: '2025-02-20'
---

https://arxiv.org/pdf/1910.10683
## Summary

The text-to-text framework is a simple way to train a single model on a wide variety of text tasks using the same loss function and decoding procedure. It has been successfully applied to generative tasks like abstractive summarization, classification tasks like natural language inference, and even regression tasks like STS-B. The framework obtained comparable performance to task-specific architectures and ultimately produced state-of-the-art results when combined with scale. The original encoder-decoder form of the Transformer architecture worked best in the text-to-text framework. Sharing the parameters in the encoder and decoder did not result in a substantial performance drop while halving the total parameter count. Most "denoising" objectives, which train the model to reconstruct randomly corrupted text, performed similarly in the text-to-text setup. The Colossal Clean Crawled Corpus (C4) comprises heuristically-cleaned text from the Common Crawl web dump. Training on in-domain unlabeled data can boost performance in a few downstream tasks. However, constraining to a single domain typically results in a smaller data set. Performance can degrade when an unlabeled data set is small enough that it is repeated many times over the course of pre-training. The basic approach of updating all of a pre-trained model’s parameters during fine-tuning outperformed methods that are designed to update fewer parameters. Multi-task learning did not match the performance of the basic approach of unsupervised pre-training followed by supervised fine-tuning. Fine-tuning after pre-training on a mixture of tasks produced comparable performance to unsupervised pre-training. Scaling up the pre-training amount or size of the baseline model produced substantial gains. Ensembling models that were fine-tuned from the same base pre-trained model performed worse than pre-training and fine-tuning all models completely separately. Ensembling models that were pre-trained together but fine-tuned separately also substantially outperformed a single model. The T5 model combines insights from the systematic study with unprecedented scale. It achieved state-of-the-art performance on 18 out of the 24 tasks considered. The model was trained on over 1 trillion tokens. The code, C4 data set, and pre-trained model weights for each T5 variant have been released to facilitate further work on transfer learning for NLP.
## Links


## Topics

![](topics/Concept/Text%20to%20Text%20Framework)

![](topics/Concept/Denoising%20Objective)

![](topics/Concept/Multi%20Task%20Learning)

![](topics/Concept/Ensemble%20Methods)

![](topics/Concept/Colossal%20Clean%20Crawled%20Corpus%20C4)

![](topics/Model/Transformer)

![](topics/Concept/Transfer%20Learning)

![](topics/Concept/Self%20Attention)

![](topics/Concept/Pre%20training)

![](topics/Concept/Fine%20tuning)