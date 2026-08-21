# Day 10 — Encoding

## Overview

Day 10 of my **Machine Learning Journey** focuses on **Encoding Categorical Features** using **Scikit-learn**.

Encoding is a preprocessing technique used to convert categorical data into numerical representations that machine learning algorithms can understand.

## Topics Covered

### 1. Encoding Categorical Features Using Scikit-learn
- Understanding categorical features
- Converting categorical variables into numerical representations
- Implementing encoding techniques using Scikit-learn

### 2. Label Encoding
- Applied **Label Encoding** on the **Titanic dataset**
- Converted categorical values into numerical labels

### 3. Ordinal Encoding
- Implemented **Ordinal Encoding**
- Used for categorical variables where categories have a meaningful order or ranking

### 4. One-Hot Encoding
- Implemented **One-Hot Encoding**
- Converted categorical values into separate binary columns
- Suitable for nominal categorical features where there is no inherent order

## Dataset

**Titanic Dataset**

The Titanic dataset was used to practically implement and understand different categorical encoding techniques.

## Tech Stack

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- VS Code

## Key Takeaways

- Categorical features often need to be converted into numerical form before model training.
- **Label Encoding** assigns numerical labels to categories.
- **Ordinal Encoding** is suitable for ordered categories.
- **One-Hot Encoding** represents categories using separate binary columns.
- The choice of encoding technique depends on the type and relationship of the categorical variable.

## Project Structure

```text
machine-learning-journey-day-10-encoding/
│
├── Day10_Encoding.ipynb
└── README.md
