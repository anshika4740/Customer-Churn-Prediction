# Customer-Churn-Prediction
📄 Project Description :
This project focuses on developing a supervised machine learning pipeline to predict customer churn using the Telco Customer Churn dataset provided by Kaggle. The workflow includes data preprocessing, feature engineering, encoding of categorical variables, model training, and evaluation.

The raw dataset was first cleaned by handling missing values and converting data types (e.g., converting TotalCharges to numeric). Categorical features were encoded using a combination of Label Encoding (for binary features) and One-Hot Encoding (for multi-class categorical variables). The target variable (Churn) was binary-encoded for classification modeling.

Several classification algorithms such as Logistic Regression, Random Forest, and XGBoost were implemented using scikit-learn to evaluate model performance based on accuracy, precision, recall, F1-score, and ROC-AUC metrics. Cross-validation was used to ensure model generalization and reduce overfitting.

This predictive system enables businesses to proactively identify customers likely to churn and take necessary retention actions.

🔧 Tech Stack:
Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

Modeling Techniques: Classification (Logistic Regression, Random Forest, XGBoost)

Evaluation Metrics: Accuracy, Confusion Matrix, ROC-AUC

