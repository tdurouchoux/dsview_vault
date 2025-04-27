---
already_read: true
link: https://www.rilldata.com/blog/the-rise-of-the-declarative-data-stack
read_priority: 3
relevance: 0
source: Data Science Weekly
tags:
- Data_Engineering
type: Content
upload_date: '2024-10-18'
---

https://www.rilldata.com/blog/the-rise-of-the-declarative-data-stack
## Summary

The article discusses the transition to a declarative data stack, emphasizing its evolution from traditional monolithic systems to modern modular approaches. It outlines the advantages of declarative systems, which focus on defining "what" outcomes are desired rather than "how" to achieve them, thus facilitating easier management of complex data operations.

Key points include:

- **Declarative vs. Imperative:** Declarative programming is simpler and less verbose, while imperative programming requires specifying each process step and is often more complex and harder to maintain.
- **Examples of Declarative Tools:** Tools like Kubernetes, dbt, Airflow, and SQLMesh exemplify this shift. Declarative architectures allow users to focus on specifying desired functionality, thereby abstracting away the implementation complexities.
- **YAML Usage:** YAML serves as a common configuration markup language, promoting clarity and ease of use across various data tools.
- **End-to-End Data Stack:** A fully integrated declarative data stack includes ingestion, transformation, serving, and visualization, with the potential for automation and governance.
- **Semantic Layers:** These layers can facilitate defining metrics and dimensions declaratively, enhancing the flexibility and maintainability of data presentations.
- **Future Prospects:** The author anticipates advancements in declarative data stacks that will enable even greater automation and simplicity, setting the stage for the next phases of development in data engineering.

This article is the first in a series that aims to deepen understanding of the emerging architecture and its implications for data professionals. Future parts will explore "BI-as-code" and practical implementations of a declarative data stack.
## Links

- [Designing a Declarative Data Stack: From Theory to Practice](https://www.rilldata.com/blog/designing-a-declarative-data-stack-from-theory-to-practice) : This blog post discusses the practical implementation of declarative data stacks and how they can evolve data workflows.
- [ELT with Kestra, DuckDB, dbt, Neon, and Resend](https://medium.pimpaudben.fr/elt-with-kestra-duckdb-dbt-neon-and-resend-5bfd62160190) : A practical guide on implementing an ELT pipeline using various modern data tools, highlighting best practices.
- [An end-to-end data stack with just DuckDB: ETL is dead, long live ETV](https://www.linkedin.com/posts/archiesarrewood_an-end-to-end-data-stack-with-just-duckdb-activity-7245362448545808385-ioK3/) : Explores the concept of Extract-Transform-Visualize (ETV) using DuckDB as the primary tool for data transformations.
- [SQLMesh: A tool for declarative transformations](https://github.com/tobymao/sqlglot) : SQLMesh is an open-source SQL parser that can be used for semantic analysis and programmatic transformation of SQL queries.
- [Why Data Teams Keep Reinventing the Wheel: The Struggle for Code Reuse in the Data Transformation Layer](https://preset.io/blog/why-data-teams-keep-reinventing-the-wheel/) : Discusses the challenges faced in data transformation, specifically focusing on the importance of code reusability.

## Topics

![](topics/Concept/Declarative%20Data%20Stack)

![](topics/Tool/dbt)

![](topics/Platform/Kubernetes)

![](topics/Library/SQLMesh)

![](topics/Concept/YAML%20Configuration)

![](topics/Platform/Airflow)