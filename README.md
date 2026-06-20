Customer Churn Prediction is a comprehensive machine learning classification project aimed at predicting whether a customer will leave (churn) a telecom company in the near future. Churn prediction is one of the most important problems in the subscription-based industry as acquiring new customers is significantly more expensive than retaining existing ones.

Objective
To build, evaluate, and compare multiple classification models to accurately predict customer churn, with a strong focus on **Recall** and **F1-Score** since correctly identifying customers likely to churn (minimizing False Negatives) is business-critical.

Dataset
- Name: Telco Customer Churn (Kaggle)
- Size: ~7,000 records, 21 features
- Target Variable: `Churn` (Yes / No)
- Key Features: Tenure, Monthly Charges, Contract Type, Internet Service, Payment Method, etc.

Key Highlights

- Exploratory Data Analysis (EDA): Analyzed churn rates, feature distributions, correlations, and relationships between categorical/numerical features and the target variable.
- Data Preprocessing: Handled missing values, converted data types, performed One-Hot Encoding for categorical variables, and feature scaling.
- Models Implemented:
  - Logistic Regression (baseline & interpretable)
  - Decision Tree Classifier
  - Random Forest Classifier
  - Support Vector Machine (SVM)
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and Classification Report.
- Advanced: Hyperparameter tuning using `GridSearchCV` for Random Forest.

Business Impact
- Helps the company identify high-risk customers early.
- Enables targeted retention campaigns (discounts, better plans, personalized offers).
- Focuses on *Recall* to ensure maximum churners are caught.

Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn (for visualization)
- Jupyter Notebook / Python Script

Results
(Random Forest usually performs best with highest F1-Score)





