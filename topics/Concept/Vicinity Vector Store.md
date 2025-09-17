---
type: Concept
---

A vicinity vector store is a data structure used to store encoded documents in a way that allows for efficient retrieval of nearest neighbors. In the context of semhash, documents are encoded using a model2vec encoder and stored in this vector store, which is backed by usearch. This setup enables fast and accurate deduplication by retrieving the nearest neighbors of incoming documents and comparing their similarity. The vicinity vector store is a key component in the semhash tool, ensuring that the deduplication process is both quick and effective.