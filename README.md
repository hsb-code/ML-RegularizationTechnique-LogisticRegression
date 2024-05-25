This repository presents a logistic regression model for predicting breast cancer, incorporating regularization techniques to improve model performance and prevent overfitting. Regularization is crucial in logistic regression to control model complexity and enhance generalization on unseen data. The project focuses on leveraging regularization methods like Ridge and Lasso Regression to achieve accurate and robust breast cancer predictions.

Regularization Techniques
1. Ridge Regression (L2 Regularization)
- Objective: Minimize the logistic loss function while adding a penalty term proportional to the square of the coefficients.
- Effect: Promotes sparsity by driving some coefficients to zero, performing automatic feature selection and reducing model complexity.
- Implementation: Adjusts the lambda parameter to achieve the desired level of regularization.

2. Lasso Regression (L1 Regularization)
- Objective: Similar to Ridge Regression but adds a penalty term proportional to the absolute value of the coefficients.
- Effect: Promotes sparsity by driving some coefficients to zero, performing automatic feature selection and reducing model complexity.
- Implementation: Adjusts the lambda parameter to achieve the desired level of regularization.

Key Features
- Breast Cancer Dataset: Utilizes a curated dataset containing medical features and corresponding breast cancer labels for model training and evaluation.
- Model Evaluation: Employs evaluation metrics such as accuracy, precision, recall, and F1 score to assess model performance.
- Regularization Strength Tuning: Demonstrates the process of tuning the lambda parameter through cross-validation to find the optimal regularization strength.
- Visualization: Includes visualizations of coefficient shrinkage and feature importance resulting from regularization.
