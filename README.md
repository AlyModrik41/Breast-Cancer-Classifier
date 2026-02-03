# 🩺 Breast Cancer Classification Using Machine Learning

This project implements and evaluates multiple supervised machine learning classifiers to predict breast cancer diagnosis (benign vs. malignant) using structured clinical features. The focus is on model comparison, validation rigor, and interpretability, aligned with real-world healthcare ML workflows.

## 📌 Problem Statement
Binary classification of breast tumors using numerical diagnostic features, with an emphasis on minimizing false negatives and ensuring robust generalization.

## 🛠️ Models Implemented
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- Voting Classifier (Hard & Soft)  
- K-Nearest Neighbors (KNN)  
- Gradient Boosting  

## 🔬 Pipeline & Methodology
- Data cleaning and feature scaling (Standardization)
- Exploratory Data Analysis (EDA) and correlation analysis
- K-Fold Cross-Validation (k = 5 ) for unbiased evaluation
- Hyperparameter tuning (Grid / Random Search)

## 📊 Best Model (VC-Soft) - Evaluation Metrics
- Accuracy: 98%
- Precision: 98%
- Recall (Sensitivity): 98%
- F1-Score: 98%

  <img width="422" height="247" alt="image" src="https://github.com/user-attachments/assets/b247e2f5-365b-4439-ba4d-b312511082dc" />\
  
- CV-Accuracy: 97%
- ROC-AUC: 100%
  
  <img width="536" height="470" alt="image" src="https://github.com/user-attachments/assets/e1af56c5-817f-407d-b47f-d96848bd1d3d" />


## 📈 Model Explainability & Analysis
- Feature importance extraction (tree-based models)
- Confusion matrices for detailed error analysis
- Comparative performance analysis across all models

## 🖼️ Visual Results
(Add your figures here)

- Feature Importance
  
  <img width="818" height="528" alt="image" src="https://github.com/user-attachments/assets/35fc7b40-746a-4e30-9eb4-5585478282bd" />

- Confusion Matrices

  <img width="709" height="625" alt="image" src="https://github.com/user-attachments/assets/7baf947c-72e2-4648-abfd-710ff41b0c6f" />

- Cross-Validation Results
  
  <img width="571" height="54" alt="image" src="https://github.com/user-attachments/assets/92d2c99b-b7ad-4c6c-9741-c2f4018996fb" />

## 🎯 Key Takeaways
- Ensemble and tree-based models achieved the strongest performance
- Voting classifiers improved stability and generalization
- Feature importance aligned with known clinical indicators

## 🚀 Tech Stack
Python · Scikit-learn · NumPy · Pandas · Matplotlib · Seaborn
