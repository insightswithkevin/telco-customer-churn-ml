# 🧠 Data-Driven Approach to Reducing Customer Attrition

## 🚀 Project Overview

This project analyzes customer churn behavior in the telecom industry using the **Telco Customer Churn dataset**. Through exploratory data analysis, interpretable modeling, and targeted business questions, we identify key churn drivers and build a predictive model to support churn reduction strategies.

The entire project is written in **Python**, with a focus on clarity, business relevance, and statistical interpretability.

---

## 🎯 Objectives

### 1. **Which customer segments churn most—and why?**

- **EDA:** Visualized churn patterns across contract type, internet service, and charges
- **Key Insights:**
  - Customers with **month-to-month contracts**, **fiber optic internet**, and **high monthly charges** are more likely to churn
  - Logistic Regression confirms these features significantly increase churn probability

---

### 2. **Can we predict churn using a simple, interpretable model?**

- **Model:** Random Forest Classifier
- **Top Predictors:** contract type (month-to-month or yearly contracts), contract length, monthly costs, and technical support service
- **Performance (Test Set):**
  - Recall (Churn): 71%
  - Precision (Churn): 55%
- **Interpretation:** Contract length and customer lifetime are strong churn indicators, especially in early lifecycle

---

### 3. **Do add-on services reduce churn?**

- **Focus:** Services like `TechSupport` and `OnlineBackup`
- **Finding:** Customers with such services show **lower churn rates**
- **Business Value:** Bundling services could be a strategic retention tool

---

## 🔧 Tools & Libraries

- `pandas`, `numpy` – Data wrangling
- `matplotlib`, `seaborn` – Visualization
- `scikit-learn` – Predictive modeling
- `statsmodels` – Statistical inference

---

## 📈 Key Takeaways

- **Early churn is predictable**: Customers with short tenure and no service bundles are at highest risk
- **Contract type is critical**: Lock-in periods (1–2 years) drastically reduce churn
- **Actionable insights**: Targeted retention offers should focus on month-to-month customers with high monthly charges and no additional services

---

## 🧠 Learning Highlights

- Built a hybrid workflow combining **EDA, statistics, and ML**
- Practiced **model interpretability and stakeholder-ready communication**
- Gained practical insight into **real-world customer behavior patterns**

---

## 📁 Dataset Info

- 📦 Source: IBM Sample Data – [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- 💡 7043 customer records, 21 features incl. demographics, services, and contract info

---
