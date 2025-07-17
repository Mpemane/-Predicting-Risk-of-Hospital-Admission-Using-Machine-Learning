# 🚑 Predicting Risk of Hospital Admission  
*A Real-World Healthcare Data Science Project*

This project explores a real-world healthcare dataset to develop a machine learning model that predicts hospital admission risk. The goal is to support early intervention by identifying high-risk patients using historical claims and behaviour data.

---

## 📊 Project Goals
- Understand and clean complex healthcare data
- Engineer predictive features from visits, claims, and medication usage
- Build interpretable models to classify hospital admission risk
- Evaluate performance using AUC, PR curve, and confusion matrix
- Use SHAP values for transparent, explainable results

---

## 🔬 Techniques Used
- Data preprocessing and feature selection
- Class imbalance handling
- Model training: Logistic Regression & XGBoost
- Hyperparameter tuning
- Model evaluation (ROC, PR curves)
- SHAP-based interpretability

---

## 🧠 Key Insights
- The data is highly imbalanced (~2.4% positive class)
- Logistic Regression serves as a transparent baseline
- XGBoost provided superior performance and recall
- SHAP values highlighted chronic illness indicators and claim history as top predictors

---

## 🛠️ Tools & Libraries
- Python: `pandas`, `numpy`, `scikit-learn`, `xgboost`
- Visualisation: `matplotlib`, `seaborn`
- Explainability: `shap`

---

## 📁 Repository Structure
hospital-admission-risk/
├── notebooks/
│ └── final_model.ipynb
├── assets/
│ └── shap_summary.png
├── requirements.txt
└── README.md
