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

The blog post introduces the `prompt()` function in MotherDuck, which integrates small language models (SLMs) like OpenAI's gpt-4o-mini directly into SQL, enabling text summarization, structured data extraction, and more. Key points include:

- **Prompt Function Overview**: The `prompt()` function supports OpenAI's gpt-4o-mini and gpt-4o models, allowing for bulk text summarization and structured data extraction. It can be used to generate, summarize, and extract structured data without separate infrastructure.
- **Use Cases**:
  - **Text Summarization**: The function can summarize text, such as converting Hacker News comments into Haikus.
  - **Unstructured to Structured Data Conversion**: The function can generate structured outputs using the `struct` and `struct_descr` parameters, facilitating the integration of LLM-generated data into analytical workflows.
- **Practical Considerations**: Effective usage requires careful consideration of tradeoffs, and testing on small samples is advised. For specific tasks like extracting email addresses, traditional SQL methods like `regex_extract` may be more efficient.
- **Availability**: The `prompt()` function is available in Preview for MotherDuck users on a Free Trial or the Standard Plan, with usage limits and quotas in place.

The post encourages users to explore the function and share feedback through the Slack channel.
## Links

- [Introducing Structured Outputs in the API](https://openai.com/index/introducing-structured-outputs-in-the-api/) : This link points to OpenAI's introduction of structured outputs in their API, which is relevant to the prompt() function's ability to return structured data.
- [GPT-4o-mini: Advancing Cost-Efficient Intelligence](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/) : This link points to OpenAI's page on GPT-4o-mini, which is the model used in the prompt() function for cost-effective and performant language processing.

## Topics

![](topics/Platform/MotherDuck)

![](topics/Model/gpt%204o%20mini)

![](topics/Model/gpt%204o)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Library/DuckDB)