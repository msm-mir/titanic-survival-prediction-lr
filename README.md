# Titanic Survival Prediction

This Project contains the implementation of a **Logistic Regression** model built completely from scratch to predict whether passengers survived the Titanic shipwreck. This project includes data exploration, preprocessing, model training, and submission to the Kaggle competition.

---

##  Project Overview

The project is implemented in a Jupyter Notebook and the goal is to build a binary classification model using Logistic Regression to predict passenger survival (0 = No, 1 = Yes). The dataset is sourced from the famous [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data).

---

## Pipeline Workflow

- Data Loading: Loading Datasets as Pandas DataFrames from the local directory.
- Exploratory Data Analysis: Visualizing survival distributions and feature correlations.
- Data Preprocessing: Droping unused features, encoding categorical features, handling missing values, and scaling numerical features.
- Model Training: Training a **Logistic Regression** classifier, plotting convergence curve, and predicting the labels.
- Evaluation Metrics: Calculating accuracy, confusion matrix, recall, precision, and f1 score.
- Inference: Making predictions on the unseen test set and generating a Kaggle-compliant submission file.

---

## Project Structure

```
├── src/
│   |── Logistic_Regression.ipynb
│   └── titanic_submission.csv
├── visualizations/
│   |── countplot_survival_rate.png
│   |── heatmap_correlation_matrix.png
│   └── model_convergence_curve.png
├── .gitignore
└── README.md
```
