---
already_read: true
link: https://motherduck.com/blog/sql-llm-prompt-function-gpt-models/
read_priority: 3
relevance: 0
source: 'Data Science Weekly '
tags:
- Natural_Language_Processing
- Large_Language_Model
type: Content
upload_date: '2024-10-18'
---

https://motherduck.com/blog/sql-llm-prompt-function-gpt-models/
## Summary

The blog post introduces the `prompt()` function in MotherDuck, which integrates small language models (SLMs) like OpenAI's gpt-4o-mini directly into SQL. This function allows users to generate, summarize, and extract structured data from text without needing separate infrastructure. Key points include:

- **Function Overview**: The `prompt()` function supports OpenAI's gpt-4o-mini and gpt-4o models. It can be used for bulk text summarization and structured data extraction. Users can specify the model to use and return structured output with the `struct` and `struct_descr` parameters.

- **Use Cases**:
  - **Text Summarization**: The function can summarize text, such as converting Hacker News comments into Haikus. It processes rows concurrently, significantly speeding up the process compared to unparallelized Python loops.
  - **Unstructured to Structured Data Conversion**: The function can generate structured outputs, extracting information like topic, sentiment, and mentioned technologies from text. The output can be stored as a STRUCT type and easily unfolded into individual columns.

- **Practical Considerations**: Users should test prompt-based use cases on small samples first. For specific tasks like extracting email addresses, traditional SQL methods like DuckDB’s `regex_extract` may be more efficient. The function is available in Preview for MotherDuck users with specific quotas.

- **Getting Started**: The `prompt()` function is available for MotherDuck users on a Free Trial or the Standard Plan. Users are encouraged to share their experiences and feedback through the Slack channel.
## Links

- [OpenAI GPT-4o-mini](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/) : OpenAI's GPT-4o-mini model, a cost-efficient and powerful language model.
- [Haiku](https://en.wikipedia.org/wiki/Haiku) : Wikipedia page on Haiku, a form of Japanese poetry.
- [Structured Outputs in OpenAI API](https://openai.com/index/introducing-structured-outputs-in-the-api/) : OpenAI's introduction of structured outputs in their API, enabling more controlled and predictable responses from language models.

## Topics

![[topics/Concept/Retrieval Augmented Generation RAG)]]

![[topics/Concept/Structured Output)]]

![[topics/Concept/Compute Units)]]

![[topics/Concept/Structured Data Extraction)]]

![[topics/Concept/Bulk Text Summarization)]]

![[topics/Concept/Constrained Decoding)]]