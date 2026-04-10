# Telco-Customer-Churn-Analysis
Machine learning model to predict customer churn using Logistic Regression, Decision Tree and Random Forest. Built with Python and Scikit-learn. Accuracy: 80.70%
# 👥 Customer Churn Predictor
### Predicting Customer Churn Using Machine Learning

---

## 📋 Project Overview
This project analyses telecom customer data to predict 
which customers are likely to cancel their subscription.
Early identification of at-risk customers enables 
proactive retention strategies, saving significant 
revenue for the business.

---

## 📊 Dataset
- **Source:** IBM Telco Customer Churn Dataset
- **Size:** 7,043 customer records
- **Features:** Demographics, services, contract 
  details, billing information
- **Target Variable:** Churn (Yes/No)
- **Class Distribution:** 73.5% Stayed, 26.5% Churned

---

## 🔍 Project Workflow
1. **Data Exploration** — Understanding structure
2. **Data Visualization** — Churn patterns by 
   contract, tenure, charges
3. **Data Preprocessing** — Encoding, scaling
4. **Model Building** — 3 classification models
5. **Model Evaluation** — Accuracy, Precision, 
   Recall, F1 Score
6. **Business Insights** — Actionable recommendations
7. **Model Deployment** — Saved with Pickle

---

## 🤖 Models Used & Results

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|----------|-----------|--------|----------|
| **Logistic Regression** | **0.8070** ✅ | 0.6584 | **0.5668** ✅ | **0.6092** ✅ |
| Decision Tree | 0.7956 | 0.6443 | 0.5134 | 0.5714 |
| Random Forest | 0.7892 | **0.6842** ✅ | 0.3824 | 0.4906 |

**Winner: Logistic Regression**
*Recall chosen as primary metric — missing a 
churning customer costs more than a false alarm!*

---

## 💡 Key Findings
- Month-to-month customers churn significantly more
- New customers (low tenure) are highest churn risk
- Logistic Regression outperformed complex models
- Random Forest had highest precision but lowest 
  recall — too conservative for churn detection

---

## 🛠️ Tools & Technologies
- **Language:** Python 3
- **Libraries:**
  - Pandas & NumPy (Data manipulation)
  - Matplotlib & Seaborn (Visualization)
  - Scikit-learn (Machine Learning)
  - Pickle (Model saving)
- **Environment:** Google Colab

---

## 📁 Project Structure
```
Customer_Churn_Predictor/
│
├── Customer_Churn_Predictor.ipynb  ← Main notebook
├── customer_churn_predictor.pkl    ← Saved model
├── churn_scaler.pkl                ← Saved scaler
├── README.md                       ← This file
└── data/
    └── WA_Fn-UseC_-Telco-Customer-Churn.csv
```

---

## 📈 Business Recommendations
1. Target month-to-month customers with 
   annual contract upgrade offers
2. Focus retention on customers in first 
   12 months of tenure
3. Score all customers monthly using this 
   model to prioritise at-risk ones
4. Offer loyalty rewards to long-term customers

---

## 👩‍💻 About The Author
**Bushira Ali Tetteh**
Data Analyst | Machine Learning | Python

📧 shiratetteh@gmail.com
💼 https://www.upwork.com/freelancers/~01ceaa1e3fdb11422a
🌍 Accra, Ghana

*Specialising in data-driven business solutions*

---

## 📬 Contact
Interested in similar analysis for your business?
- 📧 Email: shiratetteh@gmail.com
- 💼 https://www.upwork.com/freelancers/~01ceaa1e3fdb11422a
