# Dataset Story

## 1. Dataset Source
This dataset was collected from Kaggle.

Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

---

## 2. What the Creator Says About the Data
Here, I summarise what the dataset creator explains in the Kaggle data card.

### Why
- This dataset is used to help detect fraudulent credit card transactions so that financial institutions can prevent fraud affecting their customers.

### What
- The dataset contains transactions made by European cardholders over two days in September 2013.
- It includes **284,807 transactions**, among which **492 are fraudulent**.
- Most features in the dataset are numerical values obtained using **PCA (Principal Component Analysis)** for confidentiality reasons.
- The PCA-transformed features are labelled **V1 to V28**.
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

### Observations not clearly mentioned in the data card

- The dataset description states that the transactions were made by European cardholders, but it does not specify the currency used in the **Amount** column.
- The description mentions that transactions occurred over two days in September 2013 but does not specify the exact dates.  
  Based on the **Time** column in the dataset, the transactions span approximately:
  - **172,792 seconds**
  - **2,879 minutes**
  - **47.99 hours**

- There are **1,825 transactions with an amount equal to 0** in the dataset.  
  Among these:
  - **27 transactions are labelled as fraudulent**
  - **1,798 transactions are legitimate**

  The dataset description does not provide an explanation for the presence of zero-amount transactions.

---

## 4. My Summary of the Dataset
After examining the dataset, I observed the following characteristics:

- Total number of rows: **284,807**
- Total number of columns: **31**
- Feature columns: **Time, V1–V28, Amount**
- Target variable: **Class**
- The **Class column is a binary numeric variable** (0 = legitimate, 1 = fraudulent) and is treated as a categorical target in classification tasks.
- The dataset is **highly imbalanced**, with fraudulent transactions representing approximately **0.17% of the total data**.

---

## 5. Machine Learning Perspective
From a machine learning viewpoint, this dataset can be used for:

- **Supervised learning**
- **Binary classification**

Target variable: **Class**

Because the dataset is highly imbalanced, common evaluation metrics such as accuracy may not be reliable.  
Instead, metrics such as **Precision, Recall, F1-score, and Area Under the Precision-Recall Curve (AUPRC)** are more appropriate.

---

## 6. Final Conclusion
The final conclusion will be provided after completing the full analysis and modelling process.  
At this stage, the dataset has been examined from a structural and documentation perspective in order to understand its characteristics, limitations, and potential applications in fraud detection.


