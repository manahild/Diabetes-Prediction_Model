# Diabetes Classification

This repository contains the code for building and evaluating machine learning models for classifying diabetes based on various features.

## Introduction

The dataset used for this classification task contains information about individuals, including attributes such as pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age.

## Data Exploration

### Dataset Information

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 or 1) indicating whether the individual has diabetes or not

### Data Preprocessing

- Handling missing values: Replacing zeros with mean values for attributes like glucose, blood pressure, skin thickness, insulin, and BMI.
- Feature scaling: Standardizing numerical features using StandardScaler.
- Train-test split: Splitting the dataset into training and testing sets.

## Model Building

- Logistic Regression
- K-Nearest Neighbors Classifier
- Naive Bayes Classifier
- Support Vector Machine
- Random Forest
- Decision Tree

## Model Evaluation

- Accuracy: Evaluation of each model's performance on both the training and testing datasets.
- Confusion Matrix: Visual representation of model predictions compared to actual outcomes.
- Precision, Recall, F1 Score: Metrics to assess the model's performance.
- ROC Curve and AUC: Receiver Operating Characteristic curve and Area Under the Curve to evaluate the model's discriminatory ability.

## Conclusion

The models were trained and evaluated using various performance metrics, providing insights into their effectiveness in classifying diabetes based on the given features.

