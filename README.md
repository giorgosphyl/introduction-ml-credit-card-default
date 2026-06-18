# Credit Card Default Prediction

Coursework project for the **Introduction to Machine Learning** course.

This project uses a real-world credit card client dataset to predict whether a customer will default on their payment in the following month.

## Overview

The notebook performs exploratory data analysis, preprocessing, model training, and model evaluation for a binary classification problem. The dataset contains demographic, credit, payment history, bill amount, and previous payment information for 30,000 credit card clients.

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest

## Evaluation Metrics

- Accuracy
- F1-score
- ROC-AUC
- Confusion Matrix

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Key Learning Points

- The dataset is imbalanced, with more non-defaulting clients than defaulting clients.
- Feature scaling is important for models such as Logistic Regression.
- F1-score and ROC-AUC are more informative than accuracy alone for imbalanced classification.
- Random Forest achieved the strongest overall performance among the tested models.
- Credit limit and payment history can provide useful signals for default prediction.

## Dataset

The dataset file is included in the `data/` folder:

```text
data/UCI_Credit_Card.csv
```

## Notes

This project was developed for academic and portfolio purposes.
