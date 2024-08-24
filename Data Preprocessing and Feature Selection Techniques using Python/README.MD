# Data Preprocessing and Feature Selection Techniques in Python

## Overview
This repository contains a comprehensive solution to a series of data preprocessing, tokenization, and feature selection tasks using Python. The project is divided into three parts, each focusing on different aspects of data science and machine learning.

## Part 01: Data Preprocessing on Noisy Data

### Tasks:
1. **Handling Missing Values:**
   - Implemented imputation techniques to handle missing values in the dataset.
  
2. **Normality Tests:**
   - Applied normality tests to numerical columns, clearly stating hypotheses and commenting on the results.

3. **Encoding and Scaling:**
   - Encoded categorical variables and scaled numerical features to prepare the data for further analysis.

### Dataset:
- The dataset `noisy_data.csv` is included in this repository.

## Part 02: Text Tokenization and Regular Expression Extraction

### Tasks:
1. **Text Tokenization:**
   - Utilized `RegexpTokenizer()` and `word_tokenize()` from the NLTK library to tokenize the text in `wiki.txt`.
   - Removed stop words and punctuation symbols, ensuring only meaningful tokens were retained.

2. **Year Extraction:**
   - Applied regular expressions to extract all year mentions from the text.

3. **Comparison:**
   - Compared the results of the two tokenization methods and provided insights into the differences.

### Dataset:
- The text file `wiki.txt` is included in this repository.

## Part 03: Feature Selection on Melbourne Housing Dataset

### Tasks:
1. **Feature Selection Techniques:**
   - Applied various feature selection techniques, including Correlation, Chi-Square, Mutual-Information, and Random Forest Feature Importance.
  
2. **Feature Importance Visualization:**
   - Visualized the importance of selected features using bar charts.

3. **Comparison and Analysis:**
   - Analyzed and commented on the results obtained from different feature selection techniques, identifying the best and worst methods.

### Dataset:
- The Melbourne Housing dataset is available on Kaggle and can be downloaded from [this link](https://www.kaggle.com/dansbecker/melbourne-housing-snapshot/home).

## Installation and Usage

### Prerequisites
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, nltk, sklearn

### Installation
```bash
pip install pandas numpy matplotlib seaborn nltk sklearn






