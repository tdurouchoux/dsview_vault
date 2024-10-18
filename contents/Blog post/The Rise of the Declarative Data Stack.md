---
already_read: true
link: https://www.rilldata.com/blog/the-rise-of-the-declarative-data-stack?utm_source=substack&utm_medium=email
read_priority: 3
source: Data Science Weekly
tags:
- Data_Engineering
type: Content
upload_date: '2024-10-18'
---

https://www.rilldata.com/blog/the-rise-of-the-declarative-data-stack?utm_source=substack&utm_medium=email
## Summary

The article discusses the evolution and significance of the declarative data stack in modern data engineering. It highlights the transition from monolithic systems to modular, open data stacks, emphasizing a code-first approach that enhances analytics engineering practices. Key points include:

- **Declarative vs. Imperative Systems**: Declarative systems focus on defining "what" is needed, allowing the system to handle "how" to achieve it, leading to simpler, more maintainable code. Examples include SQL, Markdown, and Kubernetes.

- **Evolution of Declarative Languages**: The article traces the history from early programming languages to modern declarative frameworks, showcasing how they simplify user interactions with complex systems.

- **Components of a Declarative Data Stack**: It outlines the essential tools and processes, including ingestion, transformation, and visualization, and how they can be integrated into a cohesive stack using declarative configurations.

- **Benefits of a Declarative Approach**: This approach offers reproducibility, easier management of complex systems, and empowers non-technical users to engage with data processes without deep technical knowledge.

- **YAML as a Configuration Language**: YAML is highlighted as the preferred markup language for declarative configurations due to its readability and ease of use compared to XML and JSON.

- **Challenges and Considerations**: While declarative stacks simplify many processes, they come with a learning curve and potential debugging complexities. The article also discusses the balance between durable and ephemeral states in data management.

- **Future Directions**: The author hints at the potential for a fully integrated declarative data stack that could leverage AI and generative approaches, with upcoming parts of the series promising to explore BI-as-code and practical implementations.

Overall, the article positions the declarative data stack as a transformative approach in data engineering, advocating for its adoption to enhance efficiency and collaboration in data practices.
## Links

1. [SQLGlot](https://github.com/tobymao/sqlglot) - A library for parsing SQL queries and generating SQL code, useful for understanding and transforming SQL in a declarative manner.
2. [Dagster](https://docs.dagster.io/concepts/resources) - A data orchestrator that allows for the management of data pipelines in a declarative way, enhancing clarity and maintainability.
3. [Ibis](https://github.com/ibis-project/ibis) - A lightweight, universal interface for data transformation that allows users to write code once while interchanging SQL engines.
4. [Functional Data Engineering](https://maximebeauchemin.medium.com/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a) - An article discussing modern paradigms in data engineering that emphasize functional programming principles.
5. [Grammar of Graphics](https://towardsdatascience.com/a-comprehensive-guide-to-the-grammar-of-graphics-for-effective-visualization-of-multi-dimensional-1f92b4ed4149) - A theoretical framework for creating visualizations that focuses on the relationships between data and visual elements, relevant for declarative data visualization.
## Topics

- [[topics/Concept/Declarative Data Tools]]
- [[topics/Library/dbt]]
- [[topics/Library/SQL and SQLMesh]]
- [[topics/Library/Rill]]
- [[topics/Concept/Infrastructure as Code]]