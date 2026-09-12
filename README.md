# Insurance Classification – EE5180 Course Contest

Machine learning classification project developed for the **EE5180 Course Contest**, focusing on predicting the target class from insurance-related tabular data.

## Project Overview

This project develops and evaluates machine learning classification models on an insurance dataset containing both numerical and categorical features.

The main objective was to build a reliable classification pipeline by:

- Inspecting and preprocessing the training and test datasets
- Handling categorical variables using **Target Encoding**
- Standardizing numerical and encoded features
- Analyzing feature correlations
- Comparing multiple classification algorithms
- Evaluating models using **5-fold cross-validation**
- Selecting the best-performing classifier
- Analyzing feature importance
- Generating predictions for the Kaggle test dataset

The final model selected in the notebook was **XGBoost Classifier** based on its validation performance.

---

## Dataset

The dataset consists of insurance-related tabular features containing:

- **5 non-categorical features**
- **8 categorical features**
- A target variable for classification
- An `id` column used to identify test samples

The notebook loads:

```text
Insurance_Train.csv
Insurance_Test.csv
