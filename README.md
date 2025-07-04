# Loan-Default-Prediction-Using-Explainable-AIAI

# 🏦 Loan Approval Prediction using ML and Explainable AI (SHAP & LIME)

This project predicts loan approval using machine learning models and explains the results using **SHAP** and **LIME** to ensure transparency and interpretability — especially important in the financial domain.

---

## 📌 Project Overview

This project addresses the problem of automating loan approval decisions using a supervised machine learning approach. After building accurate models, we apply **Explainable AI (XAI)** techniques to make the decisions interpretable and trustworthy.

---

## 🧠 Objectives

- Build ML models to predict loan approval
- Evaluate model performance (accuracy, confusion matrix, ROC)
- Apply **SHAP** (global & local explainability)
- Apply **LIME** (local explanations)
- Visualize and compare model insights

---

## 📂 Dataset

- The dataset contains features like:
  - `Gender`, `Married`, `Dependents`, `Education`
  - `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`
  - `Credit_History`, `Property_Area`, etc.
- Target: `Loan_Status` (Y = Approved, N = Rejected)

---

## 📊 Models Used

- ✅ Random Forest (with hyperparameter tuning)
- ✅ XGBoost (default config)

---

## 📈 Evaluation Metrics

- Accuracy
- Confusion Matrix
- ROC-AUC Curve
- SHAP Feature Importances
- LIME Local Interpretations

---

## 🔍 Explainable AI (XAI)

### ✅ SHAP (for Random Forest)

- 📊 Summary Plot (bar & dot)
- 💧 Waterfall Plot for local prediction explanation
- 🔍 Highlights how feature values impact predictions

### ✅ LIME (for XGBoost)

- 🔎 Explains individual predictions using local surrogate model
- 📉 Shows feature conditions affecting approval

---

## 📌 Key Results

- `Credit_History`, `LoanAmount`, and `ApplicantIncome` were consistently identified as most important by both SHAP and model feature importances.
- SHAP showed how values like low credit history negatively impact predictions.
- LIME explained specific decisions and supported model transparency.

---

