# 💳 Fraud Detection

**Name:** Param Parag Koli
**Track:** Data Analytics
**Level:** 2 | **Task:** 3
**Batch:** July 2026

## Objective
Build a machine learning pipeline to detect fraudulent financial transactions from a heavily imbalanced dataset, addressing class imbalance as a core challenge.

## Files
| File | Description |
|------|-------------|
| `ParamKoli_L2_Task3.ipynb` | Main Jupyter Notebook with full analysis |
| `creditcard.csv` | Dataset used for analysis |

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn, Jupyter Notebook

## Analysis Performed
- Dataset loading and inspection
- Class imbalance visualisation
- Transaction amount and time analysis
- SMOTE oversampling to handle class imbalance
- Logistic Regression model
- Random Forest model
- Confusion matrices for both models
- AUC-ROC curve comparison
- Feature importance analysis
- Model comparison table

## Best Model
Random Forest — highest AUC-ROC and best overall metrics

## Business Recommendations
1. Deploy Random Forest as the primary fraud detection model
2. Lower classification threshold to maximise recall
3. Retrain the model periodically on new data to catch evolving fraud patterns
