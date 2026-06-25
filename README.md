## 📊 AI-Driven Customer Churn Prediction System
Telecom Company A — Data Science Project (GCI World 2026)
## 📌 Project Overview

This project focuses on building an AI-powered churn prediction system for a telecom company using real customer behavioral, billing, and device data.

Customer churn is a major business problem in the telecom industry, leading to significant revenue loss. The goal of this project is to analyze customer behavior, identify churn drivers, and build a machine learning model to predict customers at risk of leaving.

## 🎯 Objectives
Perform Exploratory Data Analysis (EDA) on telecom customer data
Identify key factors influencing customer churn
Build machine learning models to predict churn
Evaluate model performance using classification metrics
Translate data insights into actionable business strategies
## 📂 Dataset Description

The dataset contains approximately 100,000 customer records with two main components:

Client Data: demographic, account, and device-related information
Record Data: usage behavior, call activity, revenue metrics
Target Variable:
churn → indicates whether a customer left the service (1) or stayed (0)
## 🛠️ Methodology
1. Data Preprocessing
Handling missing values
Data exploration and cleaning
Feature understanding
2. Exploratory Data Analysis (EDA)
Churn distribution analysis
Device age vs churn
Usage behavior vs churn
Revenue patterns vs churn
3. Machine Learning Models

Two models were used:

Logistic Regression (baseline model)
Random Forest Classifier (final model)
4. Evaluation Metrics
Accuracy
Precision, Recall, F1-score
ROC-AUC Score
## 📈 Model Performance
Model	Accuracy	ROC-AUC
Logistic Regression	0.59	0.59
Random Forest	0.62	0.67

👉 Random Forest was selected as the final model due to better performance and ability to capture non-linear relationships.

## 🔍 Key Insights
Customers with older devices (high eqpdays) are more likely to churn
Low usage customers show higher churn probability
Declining usage and revenue are strong churn indicators
Customer behavior changes (change_mou, change_rev) are early warning signals
## 💡 Business Recommendation

To reduce churn, the telecom company should implement an AI-driven retention strategy:

## 🎯 Churn Prevention Actions:
Offer device upgrade programs for old handset users
Provide personalized plans for low-usage customers
Identify high-value customers for VIP retention programs
Use predictive scoring to proactively target at-risk customers
##📊 Expected Impact
Reduce churn rate by 10–15% (estimated)
Improve customer lifetime value (CLV)
Increase revenue stability
Enable proactive customer retention strategy
## 📁 Project Structure
├── notebook.ipynb        # Full analysis and modeling
├── client.csv            # Customer dataset
├── record.csv            # Usage history dataset
├── README.md             # Project documentation
└── slides.pdf            # Final presentation
## ⚙️ Tools & Technologies
Python
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn
Jupyter / Google Colab
## 📌 Key Takeaway

📎 References
Scikit-learn Documentation
Pandas Documentation
Telecom churn dataset (GCI World 2026)
ChatGPT (used for guidance and structuring)
