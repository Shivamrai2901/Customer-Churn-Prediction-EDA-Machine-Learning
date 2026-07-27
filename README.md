# 📊 End-to-End Telecom Customer Churn Prediction using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0?style=for-the-badge)

</div>

---

# 📌 Project Overview

Customer churn refers to customers who stop using a company's services. Predicting churn is one of the most important business problems because retaining an existing customer is often more cost-effective than acquiring a new one.

In this project, I analyzed customer data from a telecom company to understand the factors that influence churn and built machine learning models capable of predicting whether a customer is likely to leave.

The project follows the complete Machine Learning lifecycle—from data cleaning and exploratory analysis to model building, evaluation, and business recommendations.

---

# 🚀 Project Highlights

- 📊 Analyzed **7,032 telecom customer records**
- 🧹 Cleaned and transformed **20 original features into 30 model-ready features**
- 📈 Performed comprehensive Exploratory Data Analysis (EDA)
- 🤖 Built and compared **3 Machine Learning classification models**
- 🎯 Achieved **78.75% test accuracy** using Logistic Regression
- ⭐ Identified the **Top 10 factors influencing customer churn**
- 💼 Converted analytical findings into actionable business recommendations

---

# 🎯 Problem Statement

Telecommunication companies often lose customers due to increasing competition and changing customer preferences.

The objective of this project is to predict customer churn using historical customer data and identify the major factors responsible for customer attrition. These insights can help businesses develop better customer retention strategies and reduce revenue loss.

---

# 📂 Dataset Information

**Dataset:** IBM Telco Customer Churn Dataset

| Attribute | Value |
|------------|-------|
| Total Records | 7,032 |
| Original Features | 20 |
| Features After Encoding | 30 |
| Target Variable | Churn |
| Problem Type | Binary Classification |

---

# 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📋 Project Workflow

The project was completed using the following workflow:

```
Data Collection
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Data Preprocessing
      │
      ▼
Train-Test Split
      │
      ▼
Feature Scaling
      │
      ▼
Model Building
      │
      ▼
Model Evaluation
      │
      ▼
Feature Importance
      │
      ▼
Business Recommendations
```

---

# 🧹 Data Cleaning

The dataset required several preprocessing steps before it could be used for machine learning.

The following tasks were performed:

- Removed missing values
- Converted the **TotalCharges** column from object to numeric data type
- Removed unnecessary columns such as Customer ID
- Applied One-Hot Encoding to categorical variables
- Standardized numerical features using StandardScaler

These preprocessing steps ensured that the data was clean, consistent, and suitable for training machine learning models.

---

# 📊 Exploratory Data Analysis (EDA)

Several business questions were explored to understand customer behavior.

The analysis included:

- Contract Type vs Customer Churn
- Internet Service vs Customer Churn
- Customer Tenure Distribution
- Monthly Charges vs Customer Churn
- Total Charges vs Customer Churn
- Payment Method vs Customer Churn
- Paperless Billing vs Customer Churn

The objective of the EDA was not only to visualize the data but also to discover meaningful business insights that could explain why customers decide to leave.

---

# 🤖 Machine Learning Models

Three different classification algorithms were implemented and compared.

| Model | Test Accuracy |
|---------|--------------|
| Logistic Regression | **78.75%** |
| Decision Tree | 77.54% |
| Random Forest | 78.54% |

---

# 📈 Model Evaluation

The models were evaluated using multiple performance metrics instead of relying solely on accuracy.

Evaluation metrics included:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

This provided a more comprehensive understanding of each model's performance.

---

# 📊 Model Comparison

| Metric | Logistic Regression | Decision Tree | Random Forest |
|----------|--------------------|---------------|---------------|
| Accuracy | 78.75% | 77.54% | 78.54% |
| Precision | 0.62 | 0.58 | 0.63 |
| Recall | 0.52 | **0.59** | 0.48 |
| F1-Score | 0.56 | **0.58** | 0.54 |

Although Logistic Regression achieved the highest accuracy, the Decision Tree model produced the highest Recall for churn prediction, making it a strong candidate when the business objective is to identify as many churning customers as possible.

---

# ⭐ Feature Importance

Feature Importance analysis was performed using the Random Forest model to determine which variables had the greatest influence on customer churn.

The most important features identified were:

- Total Charges
- Monthly Charges
- Customer Tenure
- Internet Service (Fiber Optic)
- Electronic Check Payment Method
- Online Security
- Contract Type
- Tech Support
- Paperless Billing
- Gender

Understanding these factors helps businesses focus on customers who are at a higher risk of leaving.

---

# 💡 Key Business Insights

The analysis revealed several important findings:

- Customers with **Month-to-Month contracts** were significantly more likely to churn.
- Customers using **Fiber Optic Internet** showed higher churn rates than those using DSL.
- Customers with **shorter tenure** had a much higher probability of leaving.
- Higher **Monthly Charges** were associated with increased churn.
- Customers without **Online Security** or **Tech Support** services were more likely to churn.
- Customers with **Two-Year contracts** had the lowest churn rate.

These insights can help telecom companies design targeted retention strategies.

---

# 📌 Business Recommendations

Based on the analysis, the following recommendations can help reduce customer churn:

- Encourage customers to switch from Month-to-Month contracts to long-term plans.
- Offer loyalty rewards to newly acquired customers.
- Promote Online Security and Tech Support bundles.
- Provide discounts or personalized offers to high-risk customers.
- Improve customer engagement during the first few months of service.

---

# 📈 Future Improvements

Possible improvements to this project include:

- Hyperparameter Tuning
- Cross Validation
- XGBoost
- LightGBM
- CatBoost
- ROC-AUC Analysis
- SHAP Explainability
- Streamlit Deployment
- Model Monitoring

---

# 📂 Repository Structure

```
Customer-Churn-Prediction/
│
├── data/
│     └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│     └── Customer_Churn_Prediction.ipynb
│
├── requirements.txt
│
└── README.md
```

---

# ✅ Project Results

- Successfully analyzed **7,032 telecom customer records**
- Built and compared **three machine learning classification models**
- Achieved **78.75% test accuracy**
- Identified the major factors influencing customer churn
- Generated business recommendations to improve customer retention

---

# 📚 Key Learnings

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Machine Learning
- Model Evaluation
- Feature Importance Analysis
- Business Problem Solving
- Customer Churn Prediction

---

# 👨‍💻 Author

**Shivam Rai**

- GitHub: *Add your GitHub profile link*
- LinkedIn: *Add your LinkedIn profile link*
- Kaggle: *Add your Kaggle profile link*

---

## ⭐ If you found this project useful, consider giving it a star.
