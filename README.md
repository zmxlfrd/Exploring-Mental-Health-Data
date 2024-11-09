# Exploring Mental Health Data

This project explores mental health data to predict depression based on a variety of factors including sleep duration, academic/work stress, dietary habits, and more. The primary goal is to develop a classification model that predicts whether an individual is likely to experience depression based on these various features.

## Table of Contents

* [Datasets](#Datasets)
* [Project Description](#Project-Description)
* [Data Description](#Data-Description)
* [Exploratory Data Analysis](#Exploratory-Data-Analysis)
* [Data Preparation](#Data-Preparation)
* [Prediction Model](#Prediction-Model)
* [Conclusion](#Conclusion)

## Datasets

The data for this project is available in the [GitHub repository](https://github.com/zmxlfrd/Exploring-Mental-Health-Data).

### Data Files:

- **train.csv**: This contains both the features and the target variable (depression) used for training the model.
- **test.csv**: This contains the test dataset without the target variable, to be used for model predictions.

## Project Description

This project uses survey data to assess mental health, focusing on depression as the target variable. The features in the dataset include demographic details, academic/work information, and mental health indicators, such as sleep patterns, stress levels, and history of suicidal thoughts.

### Key Tasks:
1. **Exploratory Data Analysis (EDA)**: Explore the dataset to understand its structure, visualize relationships, and identify any data quality issues.
2. **Data Preparation**: Clean and preprocess the data for model building.
3. **Prediction Model**: Build and evaluate a machine learning model to predict depression.
4. **Model Evaluation**: Assess the performance of the model using appropriate metrics.

## Data Description

The dataset consists of survey responses, with features related to the individual's demographics, work/school life, and mental health. Here are some of the key features:

- **id**: A unique identifier for each participant.
- **Age**: Age of the individual (numerical).
- **Gender**: Gender of the individual (categorical).
- **Profession**: The individual’s profession (categorical).
- **Academic Pressure**: Academic pressure experienced by the individual (numerical).
- **Work Pressure**: Work-related stress levels (numerical).
- **Sleep Duration**: The individual's sleep patterns (categorical).
- **Dietary Habits**: The individual’s eating habits (categorical).
- **Family History of Mental Illness**: Whether the individual has a family history of mental illness (binary: Yes/No).
- **Depression**: Target variable (binary: 0 or 1), where 1 indicates the individual experiences depression.

## Exploratory Data Analysis

The dataset is first explored to understand the relationships between various features and the target variable, `Depression`. Common tasks include:

- Visualizing distributions of features.
- Checking for missing data.
- Identifying any correlations or patterns that can inform feature selection.

## Data Preparation

Data preparation steps include:

- Handling missing data.
- Encoding categorical variables.
- Normalizing numerical features for model building.

## Prediction Model

A classification model is built using machine learning algorithms such as logistic regression, decision trees, or random forests. The model is trained using the `train.csv` dataset and evaluated on the `test.csv` dataset.

### Hyperparameter Tuning

Optimizing model performance through techniques like cross-validation and hyperparameter tuning.

## Conclusion

The project concludes by discussing the model's performance, its ability to predict depression, and potential next steps for improving the prediction accuracy.

### Next Steps

- Explore additional features or data sources.
- Fine-tune the model for better accuracy.
- Develop a user interface for real-time prediction of depression based on user inputs.

---

This project provides insights into mental health data and demonstrates the power of machine learning in predicting depression.
