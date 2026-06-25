# Titanic Survival Prediction using Logistic Regression

This Project contains the implementation of a **Logistic Regression** model built completely from scratch to predict whether passengers survived the Titanic shipwreck. This project includes data exploration, preprocessing, model training, and submission to the Kaggle competition.

---

##  Project Overview

The project is implemented in a Jupyter Notebook and the goal is to build a binary classification model using Logistic Regression to predict passenger survival. The dataset is sourced from the famous [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data).

---

## Pipeline Workflow

### 1. Data Loading
- Loading Datasets as Pandas DataFrames from the local directory

### 2. Exploratory Data Analysis
- Visualizing survival distributions using `seaborn.countplot`
- Visualizing feature correlations using `seaborn.heatmap`

### 3. Data Preprocessing
- Droping unused features to eliminate noise and prevent overfitting
- Encoding categorical features using One-Hot Encoding (`pd.get_dummies`)
- Handling missing values using median imputation for numerical data
- Scaling numerical features using `StandardScaler` to normalize their distribution

### 4. Model Training
- Training a **Logistic Regression** classifier from scratch
- Plotting convergence curve using loss reduction to track optimization path and ensure proper convergence
- Predicting the labels (`0` for deceased, `1` for survived)

### 5. Model Evaluation
- Accuracy score
- Confusion matrix
- Recall score
- precision score
- f1 score

### 6. Inference
- Making predictions on the unseen test set and generating a Kaggle-compliant submission file exported as `titanic_submission.csv`.

---

## Project Structure

```
├── src/
│   └── Logistic_Regression.ipynb
├── submission/
│   |── submission_result.png
│   └── titanic_submission.csv
├── visualizations/
│   |── countplot_survival_rate.png
│   |── heatmap_correlation_matrix.png
│   └── model_convergence_curve.png
├── .gitignore
└── README.md
```
