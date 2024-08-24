# Clustering, Classification, and Dimensionality Reduction Techniques using Python

This repository contains the implementation of various machine learning techniques, including k-means clustering, classification using different supervised learning algorithms, and dimensionality reduction methods like PCA and LDA.

## Part 01: K-Means Clustering and Classification

### Dataset:
- The dataset used can be downloaded from [Kaggle](https://www.kaggle.com/shrutimechlearn/step-by-step-kmeans-explained-in-detail/data).
- Also the dataset is available in this repository.

### Tasks:
1. **K-Means Clustering:**
   - Performed k-means clustering on the dataset using Manhattan distance as the distance measure.
   - Extracted the clusters and added a separate column labeled 'Labels' with the cluster numbers assigned by the k-means algorithm.

2. **Supervised Learning Classification:**
   - Used the labeled dataset to perform classification tasks with the following algorithms:
     - Logistic Regression
     - Decision Trees
     - Random Forest
     - Naive Bayes

3. **Performance Comparison:**
   - Compared the performance of these algorithms and analyzed the homogeneity of clusters to determine if the clusters or groups are meaningful.

## Part 02: Dimensionality Reduction on Breast Cancer Dataset

### Dataset:
- The breast_cancer dataset is available in the `sklearn.datasets` library.

### Tasks:
1. **Dimensionality Reduction:**
   - Applied PCA (2 components) and LDA (1 component) on the breast_cancer dataset.

2. **Visualization:**
   - Visualized the components to assess their ability to segregate the class labels in the dataset.

3. **Variance Explained:**
   - Calculated the maximum variance explained by both components in PCA and LDA.

4. **Analysis:**
   - Provided insights into the working of PCA and LDA and determined which method is better suited for the breast_cancer dataset.


