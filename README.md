![img](https://github.com/user-attachments/assets/7376e126-88a4-4ba6-9db4-6b7667b441c0)

---
## Overview

This project focuses on detecting fraudulent credit card transactions using supervised machine learning techniques. The objective is to classify transactions as legitimate or fraudulent based on historical transaction data.

---

## Dataset

* Highly imbalanced transaction dataset
* Target variable:

  * 0 – Legitimate transaction
  * 1 – Fraudulent transaction
* Features include anonymized variables (V1–V28), Time, and Amount

---

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Project Workflow

1. Data loading
2. Data preprocessing
3. Train-test split using stratified sampling
4. Model training using Logistic Regression
5. Model evaluation
6. Performance visualization

---

## Model Evaluation Metrics

* Confusion Matrix
* ROC Curve
* AUC Score
* Classification Report

---

## Project Outputs and Visualizations

### 1. Confusion Matrix

<img width="258" height="216" alt="image" src="https://github.com/user-attachments/assets/e230c6ab-cbb4-448f-aacf-2e6d676e1572" />


* Shows correctly and incorrectly classified transactions
* Displays True Positives, True Negatives, False Positives, and False Negatives
* Helps evaluate fraud detection accuracy

---

### 2. ROC Curve

<img width="304" height="256" alt="image" src="https://github.com/user-attachments/assets/ba11276f-c44c-4735-afd4-166ca7160ebb" />


* Shows trade-off between True Positive Rate and False Positive Rate
* A higher AUC score indicates better classification performance
* Measures model’s ability to distinguish fraud from legitimate transactions

---

### 3. Transaction Amount by Class

<img width="308" height="217" alt="image" src="https://github.com/user-attachments/assets/fac89ffe-8334-4bfd-af61-d5f734864170" />


* Compares transaction amounts between legitimate and fraudulent transactions
* Helps identify spending behavior patterns
* Useful for understanding fraud characteristics

---

## Results

* Strong ROC-AUC performance
* Effective detection of fraudulent transactions
* Clear class separation despite data imbalance

---

## Future Improvements

* Apply SMOTE for better handling of class imbalance
* Experiment with Random Forest and XGBoost
* Perform hyperparameter tuning
* Deploy as a real-time fraud detection system

---




