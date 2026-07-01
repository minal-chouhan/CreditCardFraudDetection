# Credit Card Fraud Detection using Machine Learning

## Overview

This project detects fraudulent credit card transactions using Machine Learning. The model is trained on a highly imbalanced credit card transaction dataset and uses Logistic Regression to classify transactions as either legitimate or fraudulent.

The project includes data preprocessing, handling class imbalance through undersampling, model training, and performance evaluation.

## Features

* Fraudulent transaction detection
* Data preprocessing and cleaning
* Handling imbalanced datasets using undersampling
* Logistic Regression classification model
* Training and testing accuracy evaluation
* Built using Python and Scikit-learn

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Jupyter Notebook

## Dataset

The dataset contains:

* Transaction features
* Transaction amount
* Class label:

  * 0 → Legitimate Transaction
  * 1 → Fraudulent Transaction

## Project Workflow

1. Load and explore the dataset.
2. Analyze class distribution.
3. Separate legitimate and fraudulent transactions.
4. Handle class imbalance using random undersampling.
5. Create a balanced dataset.
6. Split data into training and testing sets.
7. Train a Logistic Regression model.
8. Evaluate model performance using accuracy score.

## Model Used

### Logistic Regression

The model was trained using:

```python
LogisticRegression(
    solver="liblinear",
    max_iter=1000
)
```

## Results

The model was evaluated on both training and testing datasets using Accuracy Score.

Metrics:

* Training Accuracy
* Testing Accuracy

## Future Improvements

* Implement SMOTE instead of undersampling.
* Compare multiple algorithms such as Random Forest, XGBoost, and LightGBM.
* Deploy the model using Flask or Streamlit.
* Add precision, recall, F1-score, and ROC-AUC evaluation metrics.

## Learning Outcomes

* Working with real-world financial datasets
* Handling imbalanced classification problems
* Data preprocessing and feature preparation
* Machine Learning model training and evaluation
* Fraud detection using supervised learning
