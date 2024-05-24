# End to End Heart Disease Prediction

## Project Overview

This project aims to predict whether a person has heart disease based on various medical parameters. The dataset used for this project is sourced from the UCI Cleveland repository.

## Table of Contents

1. Problem Definition
2. Data
3. Evaluation
4. Features
5. Modeling
6. Experimentation
7. Results
8. Visualisations

## Problem Definition

The objective is to develop a machine learning model that can predict the presence of heart disease in a patient based on medical parameters.

## Data

The data is sourced from the [UCI Cleveland Heart Disease dataset](https://archive.ics.uci.edu/dataset/45/heart+disease). It includes 76 attributes, but the commonly used subset includes 14 attributes.

## Evaluation

The primary metric for evaluating the model is accuracy, but other metrics like precision, recall, F1-score, and ROC-AUC are also considered to ensure a comprehensive evaluation. Feature Imporatance was also
evaluated to determine the importance of each feature on the accuracy of the model.

## Features

The dataset contains the following key features:

- `age`: Age of the patient
- `sex`: Gender of the patient
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol
- `fbs`: Fasting blood sugar
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia
- `target`: Diagnosis of heart disease (0 = no, 1 = yes)

### Exploratory Data Analysis (EDA)

EDA includes descriptive statistics, visualizations like histograms and box plots, and correlation analysis to identify relationships between features and the target variable. 
**Correlation Coefficients of the features of the dataset**: ![Screenshot 2024-05-24 123910](https://github.com/yushA987/End-to-End-Heart-Disease-Prediction/assets/114309983/e764bc69-cfd1-43f8-83e9-49a69d2f9ae7)

## Modeling

The following models were considered:

- Logistic Regression
- Random Forest
- k-Nearest Neighbors

Extensive model hyperparameter tuning was conducted using grid search and cross-validation to find the best hyperparameters for the chosen model. Ensembling techniques were also explored.
The final model was chosen based on performance metrics and hyperparameter tuning which is Logistic Regression.

## Experimentation

It involves greater research and understanding of the dataset in order to achieve a success rate of say 95%. Extensive experimentation is done with different parameters and feautures based on research in order
to gain such levels of accuracy. As this is a begineers project, this part was skipped.

## Results

The final model achieved an accuracy of 85.24%. Below are some key performance metrics:

- **Accuracy**: 82.49%
- **Precision**: 81.22%
- **Recall**: 89.09%
- **F1-score**: 84.81%
- **ROC-AUC**: 92%

### Visualizations

- **ROC Curve**: ![Screenshot 2024-05-24 121638](https://github.com/yushA987/End-to-End-Heart-Disease-Prediction/assets/114309983/e7844906-ab05-40ef-bec5-24aa57ceea6d)
- **Feature Importance**: ![Screenshot 2024-05-24 121735](https://github.com/yushA987/End-to-End-Heart-Disease-Prediction/assets/114309983/b7ee3072-de68-44b9-8318-cb2c693faf2e)
- **Scores**: ![Screenshot 2024-05-24 121828](https://github.com/yushA987/End-to-End-Heart-Disease-Prediction/assets/114309983/ef08459e-b20c-4d02-bbb7-6edaf77b0461)    
