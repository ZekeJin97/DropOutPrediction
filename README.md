# 🎓 HigherEd Dropout Prediction

This project predicts student dropout risk using multiple machine learning models, including Logistic Regression, Random Forest, and XGBoost. It was developed to identify key risk factors in student retention.

## 🧠 Project Goals

- Predict whether a student will drop out or continue based on academic and financial data.
- Build interpretable models to assist in early intervention and academic advising.

## 📊 Dataset

The dataset includes anonymized student records with features such as:

- GPA progression
- Enrollment history
- Financial standing
- Academic performance metrics

*(Dataset file included as `dataset.csv`)*

## 🛠️ Methods

- Preprocessing: Cleaned, normalized, and engineered relevant features.
- Models: 
  - Logistic Regression  
  - Random Forest  
  - XGBoost
  - (with soft-voting ensemble)
- Evaluation:
  - 5-fold stratified cross-validation
  - F1-score: ~0.91 consistently across folds
- Interpretation:
  - Feature importance analyzed via SHAP values

## 🔍 Results

- Ensemble model demonstrated stable performance and balanced precision/recall.
- SHAP visualizations helped identify major dropout risk indicators, aiding model transparency.
