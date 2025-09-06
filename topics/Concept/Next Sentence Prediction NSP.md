---
type: Concept
---

Next Sentence Prediction (NSP) is a pre-training task used in BERT to improve the model's understanding of sentence relationships. During pre-training, 50% of the time the next sentence is the actual subsequent sentence (labeled as IsNext), and 50% of the time it is a random sentence from the corpus (labeled as NotNext). This task helps the model learn to understand the relationship between two sentences, which is beneficial for tasks like question answering and natural language inference.