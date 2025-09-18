---
already_read: false
link: https://carl-mcbride-ellis.github.io/TOBoML/TOBoML.pdf
read_priority: 1
relevance: 0
source: null
tags:
- Data_Analysis
type: Content
upload_date: '2024-07-10'
---

https://carl-mcbride-ellis.github.io/TOBoML/TOBoML.pdf
## Summary

The Orange Book of Machine Learning (free version) is a comprehensive guide to making predictions using supervised regression and classification for tabular data. The book is structured into several chapters, each focusing on different aspects of machine learning.

### Key Technical Points and Takeaways:

1. **Introduction**:
   - The book emphasizes the importance of data in making predictions.
   - It introduces the fundamental assumption that data is composed of signal and noise.
   - The book discusses the importance of explainability and interpretability in machine learning models.

2. **Statistics**:
   - Covers essential statistical concepts such as centrality (mean, median, mode) and dispersion (variance, MAD, quartiles).
   - Introduces the Gaussian and Galton distributions, and discusses skewness and kurtosis.
   - Provides an overview of tests for normality and Chebyshev’s inequality.

3. **Exploratory Data Analysis (EDA)**:
   - Discusses the importance of data quality and the process of getting to know your dataframe.
   - Introduces various visualization techniques such as box plots, violin plots, and scatter plots.
   - Covers the identification of outliers, inliers, and extreme values, and the use of correlation coefficients.

4. **Data Cleaning**:
   - Addresses the handling of missing values (NULL and NaN) and the visualization of NaN with missingno.
   - Discusses different types of missing data (MCAR, MAR, MNAR) and various imputation methods.
   - Covers the handling of outliers, inliers, duplicated rows, Boolean columns, and zero variance columns.
   - Introduces feature scaling techniques such as standardization and normalization.

5. **Cross-Validation**:
   - Explains the importance of splitting data into training, validation, and test sets.
   - Introduces cross-validation techniques such as k-fold cross-validation and nested cross-validation.
   - Discusses data leakage and the concepts of covariate shift and concept drift.

6. **Regression**:
   - Covers the basics of regression, including the regression baseline model and univariate linear regression.
   - Discusses the calculation of regression coefficients (β1 and β0) using ordinary least squares and the normal equation.
   - Introduces polynomial regression, extrapolation, and the importance of explainability.
   - Covers the loss and cost functions, including gradient descent, and various metrics such as RMSE, MAE, and R2.
   - Introduces the decision tree regressor and techniques to prevent overfitting.

7. **Classification**:
   - Covers the basics of classification, including the classification baseline model and logistic regression.
   - Discusses the log-loss function and the decision tree classifier.
   - Introduces various classification metrics such as accuracy, precision, recall, F1 score, and AUC ROC.
   - Addresses the challenges of imbalanced classification and techniques to handle it.
   - Discusses the importance of classifier calibration and the use of reliability diagrams.

8. **Ensemble Estimators**:
   - Introduces the concept of ensemble estimators and the use of Random Forest.
   - Discusses weak learners and boosting techniques such as AdaBoost and Gradient Boosted Decision Trees (GBDT).
   - Introduces the convex combination of model predictions (CCMP) and stacking techniques.

9. **Hyperparameter Optimization**:
   - Discusses the importance of hyperparameter optimization and various techniques such as grid search, random search, and halving grid search.

10. **Feature Engineering and Selection**:
    - Covers the importance of feature engineering and selection in improving model performance.
    - Introduces techniques such as interaction and cross features, bucketing of continuous features, and the use of external secondary features.
    - Discusses feature selection techniques such as correlation, permutation importance, stepwise regression, LASSO, and the Boruta trick.
    - Introduces Principal Component Analysis (PCA) for dimensionality reduction.

11. **Why No Neural Networks/Deep Learning?**:
    - Discusses the limitations of neural networks and deep learning for tabular data.
    - Introduces the concept of single neuron regressors and classifiers using TensorFlow and Keras.

### Recommended Reading and Packages:
The book provides a list of recommended reading and packages for further exploration, including books on statistical learning, pattern recognition, and machine learning, as well as packages such as scikit-learn, XGBoost, LightGBM, CatBoost, and TensorFlow.

Overall, the Orange Book of Machine Learning provides a comprehensive guide to making predictions using supervised regression and classification for tabular data, covering essential statistical concepts, data cleaning techniques, cross-validation, regression, classification, ensemble estimators, hyperparameter optimization, feature engineering and selection, and the limitations of neural networks and deep learning.
## Links


## Topics

![[topics/Library/DuckDB)]]

![[topics/Concept/AutoML)]]