---
already_read: true
link: https://github.com/microsoft/data-formulator
read_priority: 0
relevance: 0
source: Data Elixir
tags:
- Data_Visualization
- AI_agent
type: Content
upload_date: '2024-10-29'
---

https://github.com/microsoft/data-formulator
## Summary

Data Formulator is an AI-powered tool from Microsoft Research designed to facilitate data visualization. It combines user interface interactions with natural language inputs, allowing users to create rich visualizations iteratively. Key features include:

1. **Data Transformation and Visualization**: Users can specify chart designs and delegate data transformation tasks to AI, which generates SQL queries to create visualizations.

2. **Multiple Dataset Support**: The tool supports working with multiple datasets simultaneously, automatically joining tables to create visualizations based on user queries.

3. **Anchoring**: Users can anchor intermediate datasets, ensuring subsequent analyses are built on the anchored data rather than the original, improving efficiency and reducing confusion.

4. **Large Data Handling**: Data Formulator can handle large datasets by uploading files to a local database powered by DuckDB, enabling dynamic data fetching and visualization.

5. **Model Support**: The tool supports various models, including OpenAI, Azure, Ollama, and Anthropic, with recommendations for models with strong code generation capabilities.

6. **External Data Loaders**: It includes data loaders for various sources like MySQL, PostgreSQL, Azure Data Explorer, Azure Blob, Amazon S3, and more.

7. **Installation and Usage**: Data Formulator can be installed via Python PIP, run in Codespaces, or built locally for customization. Users can specify chart types, drag-and-drop data fields, and provide natural language prompts to guide the AI in creating visualizations.

8. **Research and Contribution**: The project is backed by research papers and welcomes contributions, with guidelines for contributing and a code of conduct.

Overall, Data Formulator aims to streamline the data visualization process by leveraging AI to handle complex data transformations, making it easier for analysts to create and explore visualizations.
## Links

- [Data Formulator Research Paper](https://arxiv.org/abs/2408.16119) : Research paper detailing the AI-powered concept-driven visualization authoring in Data Formulator.
- [Data Formulator Video](https://youtu.be/3ndlwt0Wi3c) : Video demonstrating the capabilities and usage of Data Formulator.
- [Data Formulator Blog](https://www.microsoft.com/en-us/research/blog/data-formulator-exploring-how-ai-can-help-analysts-create-rich-data-visualizations/) : Blog post exploring how AI can help analysts create rich data visualizations using Data Formulator.

## Topics

![](topics/Tool/Data%20Formulator)

![](topics/Library/DuckDB)

![](topics/Concept/Concept%20driven%20Visualization%20Authoring)

![](topics/Concept/Data%20Threads)

![](topics/Concept/LiteLLM)