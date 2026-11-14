# ClassifyMeister — Cervical Cancer Risk Prediction

A course group project (Group 3) applying classification models to predict cervical cancer risk from patient health records.

## Dataset

`kag_risk_factors_cervical_cancer.csv` — the Kaggle cervical cancer risk factors dataset, containing patient demographic, behavioral, and medical history features with a cancer diagnosis label.

## Approach

`CancerPrediction.ipynb` (mid-term evaluation) covers the full pipeline:
- Missing-value analysis and handling (dropping sparse columns, KNN imputation for the rest)
- Feature scaling (min-max normalization)
- Outlier review
- Class imbalance correction with SMOTE
- Classification modeling (SVM, among others)

## Contents

- `Mid term evalution/` — the notebook, dataset, and mid-term presentation
- `End term evaluation/` — the final evaluation report and a supporting reference paper on Naive Bayes text classification

## Status

Academic group project (2023), submitted as a final deliverable rather than an actively maintained codebase.
