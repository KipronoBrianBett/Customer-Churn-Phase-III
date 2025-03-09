# Customer-Churn-Phase-III

SyriaTel Customer Churn Prediction
🚀 A data-driven approach to predicting and reducing customer churn at SyriaTel using machine learning.

📌 Project Overview
Customer churn is a major concern for telecom companies, leading to revenue loss and high customer acquisition costs. This project builds a predictive model to identify customers likely to churn, helping SyriaTel implement proactive retention strategies.

📂 Dataset
Source: SyriaTel Customer Data
Features Include:
Numerical: Total minutes, Total calls, Total charges
Categorical: Contract type, Payment method, International plan
Target: Churn (0 = No, 1 = Yes)
📊 Exploratory Data Analysis (EDA)
Churn Rate: 14.5% of customers churned (imbalanced dataset).
Key Findings:
High usage (minutes, charges) → Higher churn risk.
Frequent customer service calls → Indicator of dissatisfaction.
Longer account length → More stable customers.


Model Development & Evaluation
Models Tested:

Logistic Regression
Decision Tree
Random Forest 
XGBoost
Final Model: Tuned Random Forest

Accuracy: 93%
Recall (Churn): 86%
Precision (Churn): 71%
F1-Score: 78%

 Key Recommendations
1 Deploy the Random Forest model for real-time churn detection.
2 Improve customer experience by addressing frequent complaints.
3 Optimize pricing plans to retain high-usage customers.
4 Use customer feedback & competitor insights to refine predictions.
