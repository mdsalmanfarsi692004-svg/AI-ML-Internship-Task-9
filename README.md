# Task 9: Random Forest - Credit Card Fraud Detection

This repository contains a Random Forest model for detecting fraudulent credit card transactions.

## Steps Taken:
1. **Data Handling**: Generated/Loaded a stratified dataset to handle the 99:1 class imbalance.
2. **Modeling**: Trained a **Random Forest Classifier** (`n_estimators=100`) and compared it with a Logistic Regression baseline.
3. **Evaluation**: Focused on **F1-Score** and **Recall** rather than accuracy.
4. **Feature Importance**: Identified key features driving fraud detection.

## Key Results:
* **Random Forest** outperformed the baseline, capturing more fraud cases with fewer false alarms.
* **Top Features**: V14, V10, and V4 were found to be the most predictive.

## Files:
* **Task_9_Random_Forest.ipynb**: Code for training and evaluation.
* **fraud_detection_model.pkl**: Saved model for future inference.
* **Task_9_Report.pdf**: Detailed analysis.
