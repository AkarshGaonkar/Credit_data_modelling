Project Title
Credit Card Data Modelling
By: Akarsh Gaonkar

Project Motivation
In 2024, credit card default rates rose from 5.2% to 6.1%.

U.S. credit card debt jumped from $5.093 trillion in September to $5.113 trillion in October.

The increase may be due to lenient approval processes, highlighting the need for machine learning-based predictions.

Part 1: Regression Task – Predicting Credit Limit
Models & Performance (RMSE)
Model	RMSE
Linear Regression	75,209.10
Ridge Regression	75,209.10
Lasso Regression	75,229.82
Random Forest	48,246.08
XGBoost	50,068.90

🔹 Best performance: Random Forest (lowest RMSE)

Part 2: Classification Task – Predicting Default
Models & Performance (Accuracy)
Model	Accuracy
Logistic Regression	81.09%
SVM (Linear Kernel)	81.10%
SVM (Radial Kernel)	81.70%
LDA	81.09%
Neural Network	80.76%

🔹 Best performance: SVM (Radial Kernel)

Conclusions
Random Forest was most effective for predicting credit limit.

SVM with RBF kernel outperformed other models for default classification.

Model performances were consistent with expectations based on complexity and regularization strength.

Next Steps
Further hyperparameter tuning.

Consider ensemble methods or cost-sensitive classification.

Explore real-world implementation with financial institutions.
