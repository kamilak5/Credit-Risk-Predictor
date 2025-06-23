# Credit Risk Predictor

## Project Overview

This project focuses on building a machine learning model to predict credit risk using the German Credit dataset from the UCI repository:  
https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

The goal is to classify whether a client will repay the loan or default, supporting credit decision-making.

---

## Data

- Dataset: German Credit Data (UCI Machine Learning Repository)
- Features include credit amount, duration, age, and other financial and demographic attributes.
- Dataset contains 1000 samples labeled as good or bad credit risks.

---

## Approach

- Performed exploratory data analysis (EDA), preprocessing, and feature engineering.
- Tested multiple classification models: Logistic Regression, Random Forest, Gradient Boosting.
- Selected Logistic Regression as the final model due to its interpretability and balanced performance.
- Adjusted classification threshold to 0.4 to improve recall on defaulter class.
- Evaluated models using precision, recall, F1-score, and confusion matrices.

---

## Results

- Final threshold (0.4) yields:
  - Recall (defaulters): 0.72
  - Precision (defaulters): 0.65
- This improves identification of risky clients while maintaining acceptable false positive rates.

