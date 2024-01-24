Introduction
This project involves the analysis and prediction of loan risks using a real-world Loan Application dataset. The dataset provides insights into risk analysis in banking and finance services, helping to reduce the risk of financial losses when lending to customers.

Dataset Overview
Number of Rows: 307,511
Number of Columns: 122

Data Exploration and Cleaning
1. Descriptive statistics and data distribution analysis.
2. Identification and handling of duplicate values.
3. Detection and treatment of outliers.
4. Handling of NULL values through imputation and removal of attributes with high NULL percentages.

Standardizing the Values
1. Segregation and binning of high-value numeric columns.
2. Categorization and analysis of key numeric attributes.

Data Analysis
1. Visualization and analysis of outliers.
2. Gender-based loan application and default analysis.
3. Categorical variable analysis, including insights into loan types and applicant characteristics.
4. Numeric variable analysis, correlation plots, and bivariate analysis.

Machine Learning Models

Implemented various machine learning models for loan prediction:
1. Decision Tree: Identified key decision nodes, achieving an accuracy of 92.31%.
2. Logistic Regression: Achieved an accuracy of 92.34%.
3. Random Forest Classification: Accuracy of 92.31%, with a confusion matrix indicating a good fit.
4. Support Vector Machine (SVM): Achieved an accuracy of 92.31%, with a perfect confusion matrix.
5. K-Nearest Neighbors (KNN): Accuracy of 92.1%, with some limitations in prediction.
6. Gradient Boosting Regression Model: Evaluation of mean square error, indicating the model's performance.

Model Evaluation and Comparison
1. ROC Curve and AUC values for each model.
2. Precision-Recall Curve and AUC values for detailed evaluation.

Conclusion
This project provides a comprehensive analysis of loan risk factors and implements machine learning models for predicting loan outcomes. The accuracy and performance of each model are thoroughly evaluated, providing valuable insights for risk management in the banking industry.
