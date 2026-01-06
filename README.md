# 📊 Customer Churn Analysis & Explainable Data Science Project

## 🔍 Project Overview
Customer churn is a critical business problem where companies aim to identify customers who are likely to discontinue their services.  
This project delivers an **end-to-end, explainable data science solution** that predicts churn and converts insights into **actionable business strategies**.

The solution emphasizes:
- Business-aware modeling
- Explainability (not just prediction)
- Cost-sensitive decision making

---

## 🎯 Business Objective
- Predict customer churn accurately
- Minimize **business loss** using cost-based threshold optimization
- Explain model predictions to stakeholders
- Recommend **data-driven retention strategies**

---

## 🧠 Data Science Concepts Used
- Exploratory Data Analysis (EDA)
- Feature engineering & encoding
- Scaling & preprocessing
- Class imbalance handling
- Cost-sensitive learning
- Threshold optimization
- Explainable AI (SHAP)
- Business KPI evaluation

---

## 📁 Dataset
**Telco Customer Churn Dataset**

- Rows: **7,043**
- Features: **31**
- Target variable: `Churn` (Yes / No)

### Feature Categories:
- Demographics (Gender, SeniorCitizen)
- Account information (Tenure, Contract)
- Services used (Internet, Streaming, Security)
- Billing & payment details

---

## ⚙️ Models Implemented

### 1️⃣ Logistic Regression (Explainable Baseline)
- Feature scaling applied
- Interpretable coefficients & odds ratios
- Cost-based threshold optimization

### 2️⃣ Random Forest Classifier
- Captures non-linear relationships
- Higher recall for churn customers
- SHAP TreeExplainer for interpretability

---

## 📈 Model Evaluation Metrics
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix
- **Expected Business Cost**

> Special focus on **Recall for churn (Class 1)** to reduce missed churners.

---

## 💰 Cost-Based Threshold Optimization
Instead of using a default 0.5 cutoff:
- False Negatives (missed churners) have higher cost
- Threshold optimized to minimize **expected business loss**

This aligns model output with **real-world business decisions**.

---

## 🔎 Explainable AI (SHAP)

### Why SHAP?
- Explains individual predictions
- Explains global feature importance
- Improves trust in ML models

### Key SHAP Insights:
- InternetService_Fiber optic
- TotalCharges
- MonthlyCharges
- Contract type
- SeniorCitizen
- Payment method

Both **Logistic Regression** and **Random Forest** models were interpreted.

---

## 📊 Visualizations Included
- Feature distributions vs churn
- Churn rate by categorical features
- Boxplots & KDE plots
- Cohort-style churn analysis
- SHAP summary plots
- SHAP waterfall plots (individual customers)
- Expected cost comparison charts

---

## 🧪 Advanced Analysis
- **Cohort Analysis** (tenure-based churn behavior)
- **Basic Survival Analysis intuition**
- Statistical summaries by churn group
- Business KPI mapping

---

## 📌 Business Recommendations
- Target **Fiber optic users** with retention offers
- Provide discounts for **high MonthlyCharges** customers
- Promote long-term contracts
- Encourage auto-payment methods
- Special engagement programs for **senior citizens**
- Early retention actions within first **3 months of tenure**

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SHAP
- Jupyter Notebook
- Git & GitHub

---

---

## 🚀 Key Takeaways
- Business-aware ML outperforms accuracy-only models
- Explainability increases stakeholder trust
- Cost-sensitive thresholds align ML with business goals

---

## 👩‍💻 Author
**Gone Priyanka**  
Data Science | Machine Learning | Explainable AI  

---

## ⭐ If you like this project
Give it a ⭐ on GitHub and feel free to fork or contribute!
