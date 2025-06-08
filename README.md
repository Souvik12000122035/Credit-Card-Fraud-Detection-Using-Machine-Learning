# Credit-Card-Fraud-Detection-Using-Machine-Learning
This project demonstrates an end-to-end machine learning pipeline to detect fraudulent credit card transactions using advanced techniques such as oversampling (SMOTE), ensemble learning (Random Forest), and real-time prediction interfaces. The dataset is highly imbalanced, and the solution focuses on building a reliable classifier with strong generalization capabilities and low false-positive rates.

📁 Dataset
Source: Kaggle Credit Card Fraud Detection Dataset {https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud}
Features: 30 numerical features (PCA-transformed)
Target: Class (1 = Fraud, 0 = Legitimate)
Format: CSV compressed inside .zip

Model Pipeline :
1. Data Loading & Preprocessing
2. Train-Test Split
3. SMOTE Oversampling to balance class distribution
4. Random Forest Classifier training
5. Model Evaluation using Confusion Matrix, ROC AUC, and Classification Report
6. Model Export using joblib
7. Gradio Interface for real-time fraud prediction demo
