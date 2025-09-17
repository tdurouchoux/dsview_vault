---
type: Concept
---

Prompt Caching is a feature that makes the use of Contextual Retrieval more cost-effective. It allows developers to cache frequently used prompts between API calls, reducing latency by more than 2x and costs by up to 90%. This is particularly useful when the knowledge base is smaller than 200,000 tokens, as it eliminates the need for RAG or similar methods. Prompt caching helps in loading the document into the cache once and then referencing the previously cached content, reducing the one-time cost to generate contextualized chunks.