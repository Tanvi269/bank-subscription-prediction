# Bank Marketing Binary Classification (Kaggle)

## Overview
This project solves a binary classification problem based on the Bank Marketing dataset.  
The goal is to predict whether a customer will subscribe to a bank product (`y = 1`) or not (`y = 0`).

The project demonstrates an end-to-end machine learning workflow suitable for academic use and Kaggle competitions.

---

## Dataset
The dataset is provided by a Kaggle competition and includes:

- train.csv – Training data with target column `y`
- test.csv – Test data without target column
- sample_submission.csv – Submission format

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Google Colab / Jupyter Notebook  

---

## Methodology
1. Loaded the dataset using Pandas  
2. Separated features and target variable  
3. Encoded categorical features using Label Encoding  
4. Trained a Histogram-based Gradient Boosting Classifier  
5. Evaluated the model using ROC-AUC score  
6. Generated predictions for the test dataset  
7. Created the final `submission.csv` file  

---

## Model Used
Histogram-based Gradient Boosting Classifier

Key parameters:
- max_depth = 6  
- learning_rate = 0.05  
- max_iter = 150  

---

## Evaluation Metric
- ROC-AUC Score

---

## Output
The model generates a file named `submission.csv` in the required Kaggle format.

Example:
```csv
id,y
750000,0.63
750001,0.41
