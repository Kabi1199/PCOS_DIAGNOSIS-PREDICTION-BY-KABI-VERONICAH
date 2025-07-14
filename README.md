# PCOS_DIAGNOSIS-PREDICTION-BY-KABI-VERONICAH

🧬 PCOS Prediction using XGBoost & SMOTE
This project builds a machine learning model to predict the likelihood of Polycystic Ovary Syndrome (PCOS) in patients using clinical data. The model uses features such as BMI, Menstrual Irregularity, Testosterone Levels, and Antral Follicle Count.

✅ Key Features

 Model Used: XGBoost Classifier

 Class Imbalance Handling: SMOTE (Synthetic Minority Over-sampling Technique)

 Feature Scaling: StandardScaler

 Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

 Model Interpretability: Feature Importance (Permutation Importance & XGBoost Gain)

📂 Dataset Features

BMI

Menstrual_Irregularity

Testosterone_Level(ng/dL)

Antral_Follicle_Count

PCOS Diagnosis (target variable)

Performance Summary

After tuning and applying SMOTE:

Accuracy: 99%

Precision (Class 1): 100%

Recall (Class 1): 98%

F1-score (Class 1): 99%

Confusion Matrix:

lua
Copy
Edit
[[247   0]
 [  1  52]]

 
Insights

Menstrual Irregularity showed high correlation with PCOS but had lower importance in gain-based feature plots.

Permutation Importance and SHAP confirmed that it’s still a key feature in influencing predictions.

XGBoost improved model performance significantly over Logistic Regression, especially in reducing false negatives.

📁 Files in This Project

pcos_model.ipynb – main notebook with code

data.csv – dataset used for training/testing

README.md – project summary

Requirements

Python 3.x

xgboost, sklearn, pandas, matplotlib, shap, imbalanced-learn

 Author

Kabi Veronicah

Data Science Student at Cooperative University

Passionate about AI in healthcare 💡🧬
