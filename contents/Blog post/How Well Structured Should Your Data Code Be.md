---
already_read: false
link: https://blog.dagworks.io/p/how-well-structured-should-your-data
read_priority: 1
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2024-01-25'
---

https://blog.dagworks.io/p/how-well-structured-should-your-data
## Summary

The article discusses the balance between speed and structure in data science code, emphasizing that while data scientists often prioritize rapid development, this can lead to technical debt that ultimately slows them down. Key concepts include:

1. **Trade-off Dilemma**: Data scientists face a choice between adding value quickly and building robust systems, often needing to choose two out of three priorities: add value, move quickly, and build a good system.

2. **Characteristics of Good ML Code**:
   - It rarely breaks, with adequate testing and fallbacks.
   - It's easy to triage and debug.
   - It's understandable and simple.
   - It's modifiable for future needs.

3. **Mental Model - Efficient Frontier**: The efficient frontier concept from finance applies here; it suggests finding an optimal balance between system quality and speed. Data scientists should evaluate whether they are operating within this frontier.

4. **Platform Mindset**: Encourages the creation of tools and systems to help maintain a balance between moving quickly and producing high-quality systems. This includes training and adopting better practices.

5. **Hamilton Framework**: An open-source platform designed to help data scientists structure their data code effectively using simple Python functions. It adheres to quality principles while allowing for rapid development.

Overall, the article emphasizes the importance of adopting structured approaches and tools like Hamilton to effectively navigate the trade-offs inherent in data science work.
## Links

- [Hamilton: A standardized way to build dataflows in Python](http://tryhamilton.dev) : A webpage providing an overview and getting started guide for Hamilton, a framework for building data pipelines.
- [Feature Engineering with Hamilton](https://blog.dagworks.io/p/feature-engineering-with-hamilton) : A post discussing how to use Hamilton for efficient feature engineering in data science projects.
- [From Dev to Prod: A ML Pipeline Reference](https://blog.dagworks.io/p/from-dev-to-prod-a-ml-pipeline-reference) : A detailed reference post on transitioning machine learning projects from development to production.
- [Using Hamilton with Pandas in 5 Minutes](https://blog.dagworks.io/p/how-to-use-hamilton-with-pandas-in-5-minutes-89f63e5af8f5) : A tutorial guiding users on how to effectively use Hamilton with Pandas for data transformations.
- [Building a Maintainable and Modular ML Pipeline](https://blog.dagworks.io/p/building-a-maintainable-and-modular) : An exploration of best practices for creating sustainable and modular machine learning pipelines.

## Topics

![](topics/Concept/Technical%20Debt)

![](topics/Platform/Hamilton)

![](topics/Concept/Efficient%20Frontier)

![](topics/Tool/ETL%20Extract%20Transform%20Load%20Systems)

![](topics/Concept/Platform%20Mindset)