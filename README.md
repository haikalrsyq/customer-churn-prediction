# Customer Churn Prediction

## Project Overview
Customer churn is a critical business problem where retaining existing customers is often more cost-effective than acquiring new ones.
This project aims to build a machine learning model to predict customer churn and provide actionable business insights.
---
## 🎯 Objectives
- Identify customers at risk of churn
- Analyze key factors influencing churn
- Build an interpretable machine learning model for business decision-making
---
## Dataset
- Source: Telco Customer Churn Dataset
- Target Variable: `churn_value`
- Churn Rate: ~26.5%
---
## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
---
## 🔍 Workflow
1. Business Understanding
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Modeling (Logistic Regression & Random Forest)
6. Model Evaluation (ROC-AUC, F1-score)
7. Threshold Optimization
8. Business Cost Analysis
---
##  Model Performance
- Logistic Regression ROC-AUC: ~0.85+
- Optimized Threshold: 0.25
- Focus Metric: Recall & F1-score (Churn Class)
---
## Key Insights
- Customers with shorter tenure are more likely to churn
- High monthly charges increase churn risk
- Month-to-month contracts have the highest churn rate
--

## Business Recommendations
- Prioritize retention for new customers
- Offer incentives for long-term contracts
- Adjust pricing strategies for high-risk customers
