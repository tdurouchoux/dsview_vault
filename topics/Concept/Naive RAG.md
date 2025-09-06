---
type: Concept
---

Naive RAG represents the earliest methodology in the development of Retrieval-Augmented Generation (RAG). It involves a straightforward process of indexing, retrieval, and generation. In the indexing phase, data is cleaned, converted into plain text, and divided into smaller chunks. These chunks are then embedded and indexed for quick retrieval. During the retrieval phase, a user's query is encoded, and the similarity between the query and document chunks is calculated to retrieve the top K relevant documents. Finally, in the generation phase, the retrieved documents are combined with the query to generate a response. Despite its simplicity, Naive RAG faces challenges such as low precision and recall, outdated information, and issues with response generation quality.