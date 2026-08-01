# Heart Disease Prediction Using Machine Learning

## Overview

This project uses machine learning to predict the likelihood of heart disease based on patient health-related features.

Two classification algorithms were trained and evaluated:

- Logistic Regression
- Random Forest Classifier

The goal of the project was to compare the performance of both models and understand how machine learning can be applied to a healthcare-related classification problem.

## Project Workflow

1. Data loading
2. Data preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature selection
5. Train-test split
6. Model training
7. Model prediction
8. Model evaluation
9. Comparison of both algorithms

## Machine Learning Models

### Logistic Regression

A supervised classification algorithm used as one of the baseline models for predicting heart disease.

### Random Forest

An ensemble learning algorithm that combines multiple decision trees to improve prediction performance and robustness.

## Model Evaluation

The models were evaluated using accuracy, precision, recall, and F1-score.

| Metric    | Logistic Regression | Random Forest |
|-----------|---------------------|---------------|
| Accuracy  |        85.5%        |     85.5%     |
| Precision |        50.0%        |     50.0%     |
| Recall    |         6.5%        |      4.1%     |
| F1 Score  |        11.5%        |      7.5%     |

### Results Interpretation

Both models achieved the same accuracy of 85.5%. However, accuracy alone can be misleading for this dataset because the classes are imbalanced.

Logistic Regression performed better in terms of recall and F1-score, detecting more positive cases than Random Forest.

The relatively low recall indicates that both models miss a significant number of positive cases. Therefore, these models should be considered as an academic machine learning project rather than a clinically deployable prediction system.

## Visualizations

The notebook contains graphs showing the analysis and performance of the trained models.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Project Structure

```text
heart-disease-prediction-ml/
│
├── heart_disease_prediction.ipynb
└── README.md
