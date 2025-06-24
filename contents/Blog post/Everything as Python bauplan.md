---
already_read: false
link: https://www.bauplanlabs.com/blog/everything-as-python
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- MlOps
type: Content
upload_date: '2025-06-25'
---

https://www.bauplanlabs.com/blog/everything-as-python
## Summary

The article discusses the challenges of transitioning from data science prototypes to production, emphasizing that fewer than 20% of models reach production, often taking significant time. Good data scientists must blend skills in data manipulation with an understanding of software engineering, as many ML projects require robust software and infrastructure knowledge.

The author critiques two common methods for handling production transitions: shipping Jupyter notebooks directly, which leads to fragile setups, and delegating to DevOps teams, which can slow down the process and create silos. 

The proposed solution, "Everything-as-Python," leverages two tools: **marimo**, an open-source notebook that enhances reproducibility and maintainability while being Python-compatible, and **bauplan**, a cloud data platform focused on a Pythonic workflow simplifying data management and versioning.

Key features of this approach include:
- Keeping prototypes in Python, enabling direct transition to production without significant code changes.
- Using marimo to organize code functionally while connecting to data stored in S3.
- Applying Bauplan’s model decorators to manage dependencies and automate execution, leading to efficient pipelines.
- Built-in data versioning akin to Git, allowing safe experimentation and collaborative workflows.

Overall, this workflow simplifies the complexity of data operations in production environments, promoting a seamless transition from prototype to deployment without extensive restructuring. The article encourages trying out Bauplan and marimo for practical experience.
## Links

- [Bauplan Examples for Marimo](https://github.com/BauplanLabs/examples/tree/main/14-marimo) : A GitHub repository showcasing examples on how to use Marimo, a modern open-source notebook.
- [Marimo Repository](https://github.com/marimo-team/marimo) : The official GitHub repository for Marimo, including documentation and installation instructions.
- [Why Your Company Needs Data Product Managers - HBR](https://hbr.org/2022/10/why-your-company-needs-data-product-managers) : An article discussing the importance of data product managers in the context of data science and AI implementation.
- [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) : Official source of trip record data from the NYC Taxi and Limousine Commission, useful for analysis and modeling.
- [Bauplan Documentation](https://docs.bauplanlabs.com/en/latest/) : Official documentation for Bauplan, providing details on features, usage, and setup.

## Topics

![](topics/Platform/Bauplan)

![](topics/Tool/Marimo)

![](topics/Concept/Prototype%20to%20Production%20Workflow)

![](topics/Library/Polars)

![](topics/Concept/Data%20Versioning)