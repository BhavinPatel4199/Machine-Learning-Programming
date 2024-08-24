# Covid-19 Detection Using Machine Learning

## Authors
- Bhavin Patel
- Kunj Kansara

## Project Overview

The project focuses on developing a machine learning model to detect COVID-19 using various classification algorithms. The goal is to evaluate and compare the performance of different algorithms to identify the most effective method for predicting COVID-19 based on clinical and symptom data.

## Introduction

- **Context:** With the COVID-19 pandemic posing significant challenges globally, there is a need for effective and scalable detection methods. Traditional diagnostic tools may not be sufficient for rapid and widespread testing.
- **Problem Statement:** The rapid transmission of COVID-19 highlights the need for efficient detection systems. This project leverages machine learning to explore novel solutions for early detection.
- **Aim:** To compare multiple machine learning algorithms, including K-Nearest Neighbors (KNN), Random Forest, and Naive Bayes, and identify the best model for predicting COVID-19.

## Datasets

The project uses the following datasets:

1. **Covid Dataset.csv:** 
   - **Description:** The primary dataset used for training and testing the machine learning models. It contains various features related to symptoms and clinical markers relevant for predicting COVID-19.
   
2. **Raw-Data.csv:** 
   - **Description:** This file contains the initial, unprocessed data before any cleaning or preprocessing steps. It is used as the starting point for data preparation.
   
3. **Cleaned-Data.csv:** 
   - **Description:** The dataset after preprocessing steps have been applied, including handling missing values, feature selection, and encoding. This cleaned data is used for model training and evaluation.


## Methodology

- **Data Collection and Preprocessing:**
  - **Dataset:** The dataset is sourced from Kaggle, focusing on symptoms and clinical markers.
  - **Preprocessing:**
    - Handling missing values.
    - Feature selection for identifying relevant predictors.
    - Encoding categorical variables for model compatibility.

- **Algorithms Used:**
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Naive Bayes
  - Support Vector Machine (SVM)

## Implementation

- **Tools and Libraries:**
  - **Programming Language:** Python
  - **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-learn

- **Exploratory Data Analysis (EDA):**
  - Visualizations such as count plots and pie charts to understand the distribution of symptoms and their relationship with COVID-19 status.

- **Model Evaluation:**
  - Evaluated models based on accuracy, confusion matrix, ROC-AUC score, and classification reports.

## Results

- **Performance:** The Random Forest algorithm demonstrated the highest accuracy among the tested models.
- **Recommendation:** Random Forest is recommended as the most effective model for COVID-19 detection in this dataset.

## Conclusion

- **Contribution:** Provides a machine learning-based approach for early COVID-19 detection, potentially enhancing rapid intervention and risk assessment.
- **Implications:** The findings offer valuable insights into improving detection methods and supporting healthcare systems in managing the pandemic.

## Strengths

- **Comprehensive Analysis:** Thorough comparison of various algorithms for a well-rounded understanding of their performance.
- **Effective Visualizations:** Use of EDA to visualize and interpret the data distribution and its impact on detection.

## Areas for Improvement

- **Dataset Limitations:** Acknowledges potential issues with dataset completeness and representativeness, which could affect generalizability.
- **Bias Discussion:** Limited exploration of dataset biases and their impact on model robustness in diverse healthcare contexts.


