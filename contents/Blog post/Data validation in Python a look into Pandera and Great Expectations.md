---
already_read: false
link: https://endjin.com/blog/2023/03/a-look-into-pandera-and-great-expectations-for-data-validation
read_priority: 1
relevance: 0
source: null
tags:
- Data_Quality
type: Content
upload_date: '2023-04-20'
---

https://endjin.com/blog/2023/03/a-look-into-pandera-and-great-expectations-for-data-validation
## Summary

The article discusses data validation in Python, focusing on two libraries: Pandera and Great Expectations (GE). 

**Key Points:**
- Data validation ensures that data is in a suitable state for processing, impacting analytics, visualizations, and machine learning. 
- Both Pandera and GE allow data validation but differ significantly in complexity and intended use.

**Pandera:**
- Designed primarily for data scientists, it offers an intuitive, Pandas-like API to validate data with custom and predefined checks.
- Users define validation rules using a `DataFrameSchema` and can perform schema inference to simplify the creation of validation tests.
- Features include straightforward validation setup, good documentation, and ease of writing tests quickly.

**Great Expectations:**
- A heavier library aimed at building production-ready validation systems, offering a broader set of features and integration capabilities.
- Requires more initial setup (creating Data Contexts and Expectation Suites) and is more complex to navigate due to the amount of terminology.
- Provides tools for profiling data and generating comprehensive expectations through its Data Assistant, which may require refinement.

**Comparison:**
- **Learning Curve:** Pandera is easier to learn; GE has a steeper learning path due to its extensive features.
- **Validation Speed:** Pandera excels in quick test creation, while GE is more suited for complex needs requiring detailed expectations.
- **Integration:** GE is built for integration into larger systems, while Pandera focuses on simplicity in a data science context. 

**Conclusion:** 
Choose Pandera for quick, simple validations and ease of use, while opt for Great Expectations for robust, production-ready systems requiring thorough integration and functionality.
## Links

- [Kaggle Boat Sales Dataset](https://www.kaggle.com/datasets/karthikbhandary2/boat-sales) : A dataset containing boat sales data that can be used for validation tests with Pandera and Great Expectations.
- [Great Expectations Documentation](https://docs.greatexpectations.io/docs/) : The official documentation for Great Expectations, outlining its features, usage, and components for data validation.
- [Data Assistant in Great Expectations](https://docs.greatexpectations.io/docs/terms/data_assistant) : Information about the Data Assistant feature in Great Expectations, which helps in automatically generating validation tests.
- [Checkpoint Concept in Great Expectations](https://docs.greatexpectations.io/docs/terms/checkpoint) : Overview of the Checkpoint concept, which allows validation of data against expectation suites in Great Expectations.
- [Pandera Documentation](https://pandera.readthedocs.io/en/stable/index.html) : The official documentation for Pandera, offering guidance on data validation, schemas, and checks.

## Topics

![](topics/Concept/Data%20Validation)

![](topics/Library/Pandera)

![](topics/Library/Great%20Expectations)

![](topics/Tool/Data%20Profiler)

![](topics/Concept/Expectation%20Suites)