---
already_read: false
link: https://benn.substack.com/p/bi-by-another-name
read_priority: 3
relevance: 0
source: null
tags:
- Data_Analysis
- Data_Visualization
- Development_tool
type: Content
upload_date: '2025-02-14'
---

https://benn.substack.com/p/bi-by-another-name
## Summary

The author discusses the evolution and current state of universal semantic layers in data management. Key points include:

1. **Semantic Layer Definition**: A semantic layer is a computational formula that cleans, joins, and aggregates raw data into meaningful business concepts like revenue, accounts, and users.

2. **Universal Accessibility**: Current semantic layers are queryable by generic APIs, allowing data teams to mix and match BI tools. However, this approach limits analytical freedom, as it primarily supports metric extraction and lacks the flexibility for debugging or exploratory analysis.

3. **Comparison to BI Tools**: Today's semantic layers are essentially BI tools without charts. They are not universally accessible encodings of business logic that can be used by any downstream analytical application.

4. **Adoption Challenges**: Migrating to a new semantic layer is a significant undertaking. The primary benefit of moving to a universal semantic layer is to connect it to the same BI tool, which may not justify the effort.

5. **Ideal Semantic Layer**: An ideal semantic layer should support more than reporting and self-serve analysis. It should provide governance for new ways to interact with and reason about data.

6. **Data Consumption Tools**: Different people prefer different data consumption tools, reflecting real and permanent differences in opinion and preference. However, data tools need to sit on a shared source of truth.

7. **Current Limitations**: Today's semantic layers cannot support all types of data tools, as they reflect fundamentally different models for interacting with data.

8. **Potential Solutions**: The author suggests that dbt Core and SQL might offer hints at possible solutions. An aspirational semantic layer would retain the properties of both, encoding entities and computation.

9. **Future Challenges**: The next challenge for universal semantic layers is to be flexible enough to work with tools that present data in a range of different ways. Otherwise, they risk being just BI tools by another name.

The author acknowledges that while he initially proposed the concept of a metrics layer, he now sees the need for a more flexible and universal semantic layer that can support a wider range of analytical tools and use cases.
## Links

- [Holistics Blog on Amazon Metrics](https://www.holistics.io/blog/how-amazon-measures/#:~:text=In%20the%20early%20days%20of%20Amazon%2C%20the%20metrics%20deck%20was%20printed%20on%20paper.%20Today%2C%20decks%20are%20either%20printed%20or%20virtual.) : This link points to a blog post on Holistics.io discussing how Amazon measures and tracks its metrics, providing insights into the company's data management and analysis practices.
- [Holistics Blog on the Ideal Semantic Layer](https://www.holistics.io/blog/the-ideal-semantic-layer/) : This link points to a blog post on Holistics.io discussing the concept of an ideal semantic layer in data management, which is highly relevant to the content of the provided text.
- [Cube Blog on Conversational Interface for Semantic Layer](https://cube.dev/blog/conversational-interface-for-semantic-layer) : This link points to a blog post on Cube.dev discussing the development of a conversational interface for semantic layers, which aligns with the themes of data accessibility and interaction mentioned in the text.
- [Malloy Data Website](https://www.malloydata.dev/) : This link points to the website of Malloy Data, a tool mentioned in the text that is relevant to the discussion on semantic layers and data interaction.
- [MetricFlow Blog Post](https://blog.transform.co/product-news/introducing-metricflow-your-powerful-open-source-metrics-framework/) : This link points to a blog post introducing MetricFlow, a powerful open-source metrics framework, which is directly related to the discussion on semantic layers and data metrics in the provided text.

## Topics

![](topics/Concept/Universal%20Semantic%20Layer)

![](topics/Concept/Metrics%20Layer)

![](topics/Concept/dbt%20Core)

![](topics/Concept/Motif)

![](topics/Concept/Malloy)