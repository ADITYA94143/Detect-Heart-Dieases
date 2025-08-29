# Final Heart Disease ML Project

This is a complete end-to-end machine learning project for predicting **heart disease**.

## What's included
- `data/heart.csv` → Your provided dataset (1190 rows, 12 features)
- `heart_disease_final.ipynb` → Jupyter notebook with:
  - Data cleaning & renaming columns
  - Exploratory Data Analysis (EDA)
  - Preprocessing pipeline (imputation, scaling, encoding)
  - Model training (Logistic Regression + RandomForest)
  - Evaluation (accuracy, precision, recall, F1, ROC-AUC, confusion matrix, ROC curve)
  - Model export (`model.joblib`)
  - Inference helper (`predict_one()` function)

## Usage
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open the notebook:
   ```bash
   jupyter notebook heart_disease_final.ipynb
   ```
3. Run all cells to:
   - Train models
   - Compare metrics
   - Save the best model (`data/model.joblib`)
   - Test predictions with `predict_one()`

## Notes
- Column names from your dataset (e.g., `chest pain type`, `resting bp s`) are normalized automatically.
- Both Logistic Regression and RandomForest are trained with class balancing.
