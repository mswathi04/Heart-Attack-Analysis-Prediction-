# Heart-Attack-Analysis-Prediction-
This project aims to analyze and predict the likelihood of a person getting a heart attack based on various features and data available.

## Overview

Heart disease is a leading cause of death worldwide, and early detection is crucial for effective prevention and treatment. This project leverages machine learning classification techniques to predict whether a person is prone to get a heart attack or not.

## Dataset

The dataset used in this project is the Heart Attack Analysis & Prediction Dataset, which contains various medical and demographic features such as age, sex, cholesterol levels, and more. The dataset is publicly available and can be found [here]([link-to-dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)).

## Features provided in the dataset
1. Age : Age of the patient
2. Sex : Sex of the patient
3. cp : Chest Pain type chest pain type
4. trtbps : resting blood pressure (in mm Hg)
5. chol : cholestoral in mg/dl fetched via BMI sensor
6. fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg : resting electrocardiographic results
8. thalachh : maximum heart rate achieved
9. exng : exercise induced angina (1 = yes; 0 = no)
10. oldpeak : Previous peak

## Objective

1. Identify predictor and response variable.
2. apply different classification methods to below 4 cases and analyse its performance,
\n   i   train_size : test_size = 80 : 20 and Threshold = 0.5
\n   ii  train_size : test_size = 80 : 20 and Threshold = 0.6
\n   iii train_size : test_size = 70 : 30 and Threshold = 0.5
\n   iv  train_size : test_size = 70 : 30 and Threshold = 0.6

## Methodology

1. **Data Preprocessing**: The dataset is cleaned and preprocessed to handle missing values, encode categorical variables, and scale numerical features if necessary.

2. **Exploratory Data Analysis (EDA)**: Exploratory data analysis is performed to gain insights into the distribution of features, correlations, and potential patterns in the data.

3. **Model Training**: Several machine learning classification algorithms are trained on the preprocessed data to predict the likelihood of a heart attack. The models are evaluated using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.
