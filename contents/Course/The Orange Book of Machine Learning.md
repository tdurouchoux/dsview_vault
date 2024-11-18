---
already_read: false
link: https://carl-mcbride-ellis.github.io/TOBoML/TOBoML.pdf
read_priority: 1
source: null
tags:
- Supervised_Learning
- Data_Visualization
- Data_Quality
- Feature_Engineering
- Model_evaluation
- Statistics
type: Content
upload_date: '2024-07-10'
---

![](artefacts/TOBoML.pdf)
## Summary

The Orange Book of Machine Learning provides a comprehensive guide to making predictions using supervised regression and classification techniques, primarily focusing on tabular data. The book is structured into several key chapters:

1. **Introduction**: Discusses the fundamentals of statistical modeling, interpolation vs. curve fitting, sources of uncertainty, and the importance of explainability and interpretability in models.

2. **Statistics**: Covers essential statistical concepts such as central tendency (mean, median, mode), dispersion (variance, MAD), Gaussian distribution, and Chebyshev’s inequality.

3. **Exploratory Data Analysis (EDA)**: Emphasizes the importance of understanding data quality, descriptive statistics, and visualization techniques like box plots and scatter plots.

4. **Data Cleaning**: Addresses handling missing values, outliers, and feature scaling, along with techniques for cleaning data to prepare it for modeling.

5. **Cross-validation**: Explains the importance of model evaluation through techniques like train-test split, k-fold cross-validation, and the risks of data leakage.

6. **Regression**: Introduces linear regression, polynomial regression, and decision tree regression, discussing loss functions, metrics, and the concept of overfitting.

7. **Classification**: Focuses on logistic regression, decision trees, and various classification metrics such as accuracy, precision, recall, and AUC-ROC, along with strategies for handling imbalanced datasets.

8. **Ensemble Estimators**: Discusses methods like Random Forests and boosting techniques (e.g., AdaBoost, Gradient Boosting) to improve model performance through aggregation of multiple estimators.

9. **Hyperparameter Optimization**: Describes techniques for tuning model hyperparameters using grid search, randomized search, and other methods to enhance model performance.

10. **Feature Engineering and Selection**: Highlights the importance of creating new features and selecting relevant ones to improve model accuracy, including techniques like permutation importance and LASSO.

11. **Why No Neural Networks/Deep Learning?**: Argues against the use of deep learning for tabular data, suggesting that traditional models like decision trees and ensemble methods often outperform neural networks in this context.

The book emphasizes practical applications using Python, particularly with libraries like scikit-learn, and provides numerous code examples and visualizations to aid understanding. It serves as a valuable resource for data scientists looking to enhance their skills in machine learning and predictive modeling.
## Topics

![](topics/Library/scikit%20learn)

![](topics/Library/pandas)

![](topics/Library/missingno)

![](topics/Library/eli5)