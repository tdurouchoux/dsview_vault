---
type: Library
---

Word2Vec is a popular method for learning word embeddings, which represent words as dense vectors in a continuous vector space. These embeddings capture semantic relationships between words, such as analogies (e.g., 'king' - 'man' + 'woman' ≈ 'queen'). Word2Vec can be trained using either the Continuous Bag-of-Words (CBOW) or Skip-gram architectures. The embeddings are context-independent at lookup time, meaning the same word always maps to the same vector regardless of its context in a sentence.