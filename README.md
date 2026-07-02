# 📉 Customer Churn Analysis

![Machine Learning](https://img.shields.io/badge/ML-Classification-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📌 Project Overview

A data-driven **Customer Churn Analysis** project that identifies customers likely to leave a service. Using exploratory data analysis and machine learning classification models, this project uncovers key churn drivers and provides actionable retention strategies.

## 🎯 Objectives

- Analyze customer behavior patterns leading to churn
- Identify key features that influence customer attrition
- Build predictive classification models to flag at-risk customers
- Provide data-backed retention strategies to reduce churn rate
- Visualize churn patterns across demographics and usage metrics

## 📂 Dataset

- **Source:** [Kaggle Datasets](https://www.kaggle.com/datasets)
- **Records:** 7,000+ customer records
- **Features:** Customer ID, Gender, Tenure, Monthly Charges, Contract Type, Internet Service, Payment Method, Churn (Target)

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Pandas & NumPy | Data wrangling |
| Scikit-Learn | ML models & evaluation |
| XGBoost | Gradient boosting classifier |
| Microsoft Excel | Development environment |

## 📁 Live Dashboard


<img width="1346" height="505" alt="1" src="https://github.com/user-attachments/assets/dbe5c72b-7f84-4db9-beac-e9c6eb3d0324" />

<img width="1338" height="384" alt="2" src="https://github.com/user-attachments/assets/9eaeaeed-ce21-4379-918a-dcfa2278fb93" />

<img width="1331" height="237" alt="3" src="https://github.com/user-attachments/assets/971e771c-aabf-474d-962b-dd218517d9b1" />

<img width="648" height="368" alt="4" src="https://github.com/user-attachments/assets/599a2ea9-0d87-41ed-9103-5eb5849336aa" />

<img width="656" height="383" alt="5" src="https://github.com/user-attachments/assets/0a346431-ad27-4ff4-8e25-9e0f99e250d5" />


### Churn Distribution
- Overall churn rate: **26.5%**
- Month-to-month contracts: **42% churn rate** vs **3% for 2-year contracts**
- Customers with fiber optic internet: **30% higher churn** than DSL users

### Top Churn Drivers
| Rank | Feature | Importance |
|------|---------|-----------|
| 1 | Contract Type | 0.28 |
| 2 | Tenure (months) | 0.22 |
| 3 | Monthly Charges | 0.18 |
| 4 | Internet Service Type | 0.14 |
| 5 | Payment Method | 0.10 |

### Critical Insights
- **New customers (0-12 months)** have **3x higher churn risk**
- Customers paying **>$70/month** churn at **35% rate**
- **Electronic check** payment users churn **2x more** than auto-pay users
- Customers without **tech support** churn at **40% rate**

## 🤖 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | AUC-ROC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | 80.5% | 0.78 | 0.75 | 0.76 | 0.84 |
| Random Forest | 83.2% | 0.81 | 0.79 | 0.80 | 0.87 |
| **XGBoost** | **85.8%** | **0.84** | **0.82** | **0.83** | **0.90** |
| SVM | 82.1% | 0.80 | 0.77 | 0.78 | 0.86 |

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

 📬 Contact
Anushree Saha

LinkedIn: www.linkedin.com/in/anushree-saha-4bb3a4368
- Email: riyaggit58@gmail.com
