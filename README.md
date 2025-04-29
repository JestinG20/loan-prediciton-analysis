# 🏦 Loan Prediction Analysis & Classification

This project focuses on analyzing and predicting loan approval status using classification models. The goal is to understand the factors that influence whether a loan will be approved and to build a model that can predict this outcome accurately based on applicant data.

## 📊 Project Overview

The analysis includes:
- Importing and exploring the loan dataset
- Data cleaning and preprocessing
- Handling missing values and encoding categorical variables
- Exploratory Data Analysis (EDA) using visualizations
- Model training using Logistic Regression
- Evaluating model performance

## 📁 Dataset Features

The dataset includes various customer attributes such as:
- **Gender**
- **Marital Status**
- **Dependents**
- **Education**
- **Self Employed Status**
- **Applicant & Coapplicant Income**
- **Loan Amount and Term**
- **Credit History**
- **Property Area**
- **Loan Status** (Target variable)

These features are used to determine whether a loan should be approved or not.

## 📈 Modeling & Evaluation

A Logistic Regression classifier was trained on the processed dataset. The model was evaluated using:
- **Accuracy Score**
- **Confusion Matrix**

Visualization of the confusion matrix helps interpret the performance in terms of true positives, true negatives, false positives, and false negatives.

## 📌 Key Insights

- Credit history is a strong indicator of loan approval.
- Applicant income, while important, is not always a decisive factor alone.
- Data preprocessing (like filling missing values and encoding) plays a crucial role in model success.

## 📷 Visualizations

The notebook contains multiple visualizations including:
- Bar plots for categorical feature distribution
- Heatmaps for missing data and correlation
- Count plots comparing feature distributions across loan status

These visual aids help uncover trends and patterns in the dataset that influence the model.

## 🙌 Acknowledgments

This project is inspired by a common dataset used in machine learning competitions, for beginner-friendly classification tasks.
