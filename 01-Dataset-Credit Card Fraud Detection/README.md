# Dataset Story

## 1. Dataset Source
This dataset was collected from Kaggle.

Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

---

## 2. What the Creator Says About the Data
Here I summarize what the dataset creator explains in the Kaggle data card.

Why:
- This dataset is used to help detect fraudulent credit card transactions so that financial institutions can prevent fraud affecting their customers.

What:
- The dataset contains transactions made by European cardholders over two days in September 2013.
- It includes **284,807 transactions**, among which **492 are fraudulent**.
- Most features in the dataset are numerical values obtained using **PCA (Principal Component Analysis)** for confidentiality reasons.
- The PCA-transformed features are labeled **V1 to V28**.
- Only two original features remain: **Time** and **Amount**.
- The **Time** feature represents the number of seconds elapsed between each transaction and the first transaction in the dataset.
- The **Amount** feature represents the monetary value of the transaction.
- The **Class** column is the target variable:
  - **1 indicates a fraudulent transaction**
  - **0 indicates a legitimate transaction**
- The dataset is **highly imbalanced**, with fraudulent transactions representing a very small fraction of the total data.
- Because of this imbalance, the dataset creators suggest using evaluation metrics such as the **Area Under the Precision-Recall Curve (AUPRC)** rather than relying only on accuracy.

---

## 3. Comparing the Description with the Dataset
After examining the dataset, I compared the actual data with the description.

Observations of what was not mentioned:
- The dataset contains additional columns not clearly explained.
- Some columns have missing values.
- Some features appear to be categorical variables.
- There are some transactions with an amount of zero in the column of the amount, but there is no explanation for this in the data card.

---

## 4. My Summery of the Dataset
After examining the dataset, I observed:

- Total number of rows: 284807
- Total number of columns: 31
- Presence of numerical and categorical features
- Target variable: Class, it's also Catogerial
- The dataset is imbalanced
- Feutuer cloumns are 

---

## 5. Machine Learning Perspective
From a machine learning viewpoint, this dataset can be used for:

- Supervised learning
- Classification task

Target variable: "class"

---

## 6. Final Conclusion
It will be provided after completing all the work, from a data scientist's perspective. 








