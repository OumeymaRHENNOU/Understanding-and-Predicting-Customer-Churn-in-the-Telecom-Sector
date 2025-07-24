# 📊 Customer Churn Prediction Using Machine Learning

A data science project that aims to predict whether a customer will churn (leave) a telecom service using machine learning models such as Logistic Regression, Random Forest, XGBoost, SVM, and K-Nearest Neighbors. This project also handles data imbalance and applies hyperparameter tuning to optimize model performance.

---

## 🧠 Project Objective

The goal is to develop an accurate and interpretable model to **predict customer churn**, helping telecom companies retain customers by taking proactive actions.

---

## 📌 Dataset

- **Source**: [IBM Telco Customer Churn Dataset](https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/)
- **Columns**: Customer demographics, services subscribed, account info, and churn label.

---

## 🔧 Technologies & Libraries

- Python 3
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn 

---

## 📉 Handling Imbalanced Data

- Used **`scale_pos_weight`** in XGBoost
- Explored **precision, recall, and F1-score** alongside accuracy
- Could be extended with:
  - SMOTE
  - RandomUnderSampler / OverSampler (optional future improvements)

---

## 📝 Key Findings

- Most customers who churn have month-to-month contracts, no online security, and multiple support requests.
- Class imbalance significantly affects model learning; models biased toward majority class without balancing.
- Random Forest and XGBoost performed best on this dataset with F1-scores around **0.55 - 0.57** for the minority class.

---

## 📈 Future Improvements

- Perform **hyperparameter tuning** using `GridSearchCV`
- Add **model explainability** with SHAP or LIME
- Deploy model using Flask or Streamlit for demonstration
- Improve recall on the churn class using resampling methods

---

## 💬 Contact

For any questions or collaboration opportunities:

**Oumeyma Rhennou**  
[📧 oumeyma.rhennou01@gmail.com]


