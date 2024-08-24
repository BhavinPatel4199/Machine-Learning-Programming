# Deep Learning for Multi-Class Classification with Imbalanced Data

This repository presents a deep learning experiment for a multi-class classification task using a customer segmentation dataset. The experiment involves handling imbalanced data, training a neural network, and comparing results with and without data sampling techniques.

## Dataset
The dataset used in this project can be found on Kaggle and includes two files: `train.csv` and `test.csv`. The target variable, `var_1`, contains three categories with slight class imbalance:
- Cat_6: 65%
- Cat_4: 13%
- Other: 22%

-- Also dataset used is uploaded in this repository.

## Project Structure
1. **Data Preparation:**
   - Shuffling the data before training to ensure randomness.
   - Splitting the `train.csv` into training and validation sets.

2. **Model Design and Training:**
   - Designed a neural network model (e.g., DNN) for multi-class classification.
   - Trained the model using the training set.

3. **Model Tuning and Evaluation:**
   - Used validation data for tuning the model.
   - Monitored the F1-score and applied early stopping using the Keras library.
   - Calculated classification metrics using the test data.
   - Generated loss and F1-score curves for both training and validation sets.
   - Generated a ROC-AUC curve to assess model accuracy and determine the optimal threshold.

4. **Handling Imbalanced Data:**
   - Applied oversampling to increase instances of the minority class in the training set.
   - Repeated the steps from data preparation to model evaluation using the sampled data.
   - Compared and commented on the results obtained from the original and sampled data distributions.


