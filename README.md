# Heart Failure Clinical Records - Classification & Survival Prediction

This project builds a Machine Learning model to predict heart failure mortality using clinical records.

## 📌 Project Highlights
- **Dataset:** Heart Failure Clinical Records (`heart_failure_clinical_records_dataset.csv`)
- **Target Variable:** `DEATH_EVENT` (Binary Classification)
- **Class Balancing:** Applied **SMOTE** on training set to handle class imbalance.
- **Scaling:** Features standardized via `StandardScaler`.
- **Optimization:** Hyperparameter tuning using `GridSearchCV` on Random Forest.

## 📊 Final Model Metrics (Tuned Random Forest)
- **Accuracy:** 83.33%
- **Precision (High Risk):** 80.00%
- **Recall (High Risk):** 63.16%
- **F1-Score:** 70.59%
