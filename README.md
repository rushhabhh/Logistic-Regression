# Iris-Flower-Classification

This repository contains a simple yet effective machine learning project to classify iris flowers using logistic regression. It serves as a foundational project to understand classification techniques and evaluate model performance.

## Overview

The objective of this project is to classify iris flowers into one of three species — *Setosa*, *Versicolor*, or *Virginica* — based on features such as sepal length, sepal width, petal length, and petal width.

## Project Link

You can explore the entire workflow and visualizations in the provided Jupyter Notebook.

**Notebook**: [`irisflower_logistic_regression.ipynb`](./irisflower_logistic_regression.ipynb)

## Project Features

The project covers the following steps:

- **Data Loading**: Using the classic Iris dataset from scikit-learn.
- **Data Exploration**: Understanding feature distributions and target class balance.
- **Data Preprocessing**: Converting to pandas DataFrame, encoding the target, and splitting into training and testing sets.
- **Model Training**: Applying logistic regression using scikit-learn.
- **Evaluation Metrics**:
  - Accuracy
  - Classification Report (Precision, Recall, F1-Score)
  - Confusion Matrix
- **Visualization**: Heatmap of confusion matrix for intuitive model performance understanding.

## Dataset

The dataset consists of 150 observations with the following features:

- Sepal Length (cm)  
- Sepal Width (cm)  
- Petal Length (cm)  
- Petal Width (cm)  
- Target Species (`Setosa`, `Versicolor`, `Virginica`)

## Key Findings

- Logistic Regression achieved high accuracy on the test data, effectively distinguishing between the three species.
- The confusion matrix showed minimal misclassification, especially for `Setosa`, which was perfectly predicted.
- The model demonstrated balanced performance across precision, recall, and F1-score.

## How to Use

To run or explore the project:

1. Clone or download this repository
2. Create and activate a virtual environment (optional but recommended)
3. Install necessary packages
4. Run the Jupyter notebook:
