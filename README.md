# Credit Card Fraud Detection using Machine Learning

## Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. Credit card fraud is a major financial security issue, and this model aims to identify fraudulent transactions accurately while minimizing false positives.

The dataset used for this project is highly imbalanced, making it a real-world classification problem. Various preprocessing techniques and evaluation metrics are used to build a reliable fraud detection model.

---

## Objectives

* Detect fraudulent credit card transactions.
* Handle imbalanced data effectively.
* Train and evaluate a machine learning classification model.
* Improve fraud detection accuracy while reducing false alarms.

---

## Dataset

The dataset contains anonymized credit card transactions with the following characteristics:

* Features: Numerical features obtained after PCA transformation (`V1` to `V28`)
* Additional Features:

  * `Time`
  * `Amount`
* Target Variable:

  * `Class`

    * `0` → Legitimate Transaction
    * `1` → Fraudulent Transaction

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

---

## Machine Learning Workflow

1. Data Collection
2. Data Exploration
3. Data Preprocessing
4. Handling Class Imbalance using SMOTE
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Fraud Prediction

---

## Model Used

* Support Vector Machine (SVM)

---

## Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics provide a better understanding of model performance, especially for imbalanced datasets.



## Results

The trained SVM model successfully classifies legitimate and fraudulent transactions with high performance. SMOTE helps improve the model's ability to identify fraudulent transactions by balancing the dataset.



## Project Structure


## Future Improvements

* Experiment with XGBoost, Random Forest, and LightGBM.
* Perform Hyperparameter Tuning.
* Deploy the model using Flask or FastAPI.
* Build a real-time fraud detection web application.


## Conclusion

This project demonstrates the use of Machine Learning for detecting fraudulent credit card transactions. By applying preprocessing techniques, handling class imbalance with SMOTE, and training an SVM classifier, the model effectively distinguishes fraudulent transactions from legitimate ones.
