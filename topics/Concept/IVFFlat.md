---
type: Concept
---

IVFFlat (Inverted File with Flat quantization) is an indexing technique used in vector search to partition the vector space into clusters. During a search, it identifies the nearest clusters and performs the search within those clusters. IVFFlat is known for its lower memory footprint and faster index creation compared to other methods, but it requires specifying the number of lists (clusters) upfront, which can impact recall and query performance.