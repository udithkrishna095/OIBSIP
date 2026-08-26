# Iris Flower Classification

## Oasis Infobyte Data Science Internship — Task 1

## Project Overview

This project focuses on building a machine learning classification model to
predict the species of an Iris flower using its sepal and petal measurements.

The project follows a complete data science workflow, including data
understanding, exploratory data analysis, feature selection discussion,
model training, evaluation, and model comparison.

## Dataset

The Iris dataset is loaded directly from scikit-learn using:

`sklearn.datasets.load_iris()`

The dataset contains:

- 150 observations
- 4 numerical features
- 3 target classes

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes

- Setosa
- Versicolor
- Virginica

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Data Loading

The Iris dataset was loaded directly using scikit-learn's built-in dataset
loader.

### 2. Data Understanding

The dataset was examined using:

- Dataset shape
- Data types
- Missing-value checks
- Descriptive statistics

### 3. Exploratory Data Analysis

The following visualizations were created:

- Species distribution plot
- Pairplot
- Box plots for each feature

The exploratory analysis showed that petal length and petal width provide
stronger separation between the Iris species, while the sepal measurements
show greater overlap.

### 4. Feature and Target Separation

The four flower measurements were used as input features (`X`), while the
flower species was used as the target (`y`).

### 5. Train-Test Split

The dataset was divided into:

- 80% training data
- 20% testing data

A fixed random state was used to make the experiment reproducible.

### 6. Machine Learning Models

Two classification algorithms were trained:

1. Decision Tree Classifier
2. Logistic Regression

### 7. Model Evaluation

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

### 8. Model Comparison

The performance of both classifiers was compared using their test-set
accuracy and classification results.

The model with the highest test accuracy was selected as the
best-performing model for this project.

## Results

The exact model results are available in the accompanying Jupyter Notebook,
including the accuracy, confusion matrices, and classification reports for
both classifiers.

## Key Findings

- The dataset contains 150 Iris flower observations.
- The three species are evenly represented.
- No missing values were found.
- Petal length and petal width showed stronger species separation during EDA.
- An 80/20 train-test split was used.
- Two classification algorithms were compared.
- Multiple evaluation metrics were used to assess model performance.

## Project Structure

```text
Task 1 - Iris Flower Classification/
│
├── Iris_Flower_Classification.ipynb
└── README.md