# E-commerce Customers — Linear Regression Practice

## About This Project

This repository contains a **beginner-level practice project** using Python and Linear Regression to explore customer behaviour and predict **Yearly Amount Spent**.

The project was created as part of my practical learning in **Data Science and Machine Learning**. It focuses on understanding the basic workflow of a supervised machine-learning project, from exploring a dataset to training and evaluating a regression model.

This is a **learning/practice project**, so the main goal is to understand the modelling process and build confidence with the tools rather than develop a production-ready predictive system.

---

## Dataset

The dataset used in this project is the **E-commerce Customers** dataset, sourced from Kaggle.

**Original dataset:**
[Kaggle — Linear Regression E-commerce Dataset](https://www.kaggle.com/datasets/kolawale/focusing-on-mobile-app-or-website?utm_source=chatgpt.com)

The dataset contains information about customers' interaction with an e-commerce platform, including their engagement with the company's mobile app and website.

### Main Variables

The regression model uses the following variables as features:

* **Length of Membership**
* **Time on App**
* **Avg. Session Length**
* **Time on Website**

The target variable is:

* **Yearly Amount Spent**

---

## Project Objective

The objective is to investigate whether customer engagement variables can be used to predict **Yearly Amount Spent**.

The project uses **multiple linear regression**, where several independent variables are used together to estimate a continuous outcome.

---

## Project Workflow

The notebook follows a simple machine-learning workflow:

### 1. Import Libraries

Python libraries are imported for:

* Data manipulation
* Numerical analysis
* Data visualization
* Statistical analysis
* Machine learning

### 2. Load the Dataset

The Kaggle dataset is loaded into a Pandas DataFrame.

### 3. Explore the Data

The dataset is examined using:

* `head()`
* `info()`
* `describe()`

These steps provide an initial understanding of the dataset structure and numerical variables.

### 4. Exploratory Data Analysis

Visualizations are used to explore relationships between the variables.

The analysis includes:

* Pair plots
* Correlation analysis
* Scatter plots
* Regression plots

### 5. Select Features and Target

Four customer behaviour variables are selected as predictors:

```text
Length of Membership
Time on App
Avg. Session Length
Time on Website
```

The target variable is:

```text
Yearly Amount Spent
```

### 6. Split the Dataset

The data is divided into training and testing sets.

* **80%** → Training data
* **20%** → Testing data

The training data is used to fit the model, while the testing data is used to evaluate its predictions.

### 7. Train the Linear Regression Model

A Linear Regression model from **Scikit-learn** is trained using the selected features.

### 8. Interpret the Coefficients

The regression coefficients are examined to understand how the model associates each feature with the predicted yearly spending while considering the other included variables.

### 9. Generate Predictions

The trained model produces predictions for the test dataset.

### 10. Evaluate the Model

The following metrics are calculated:

* **MAE — Mean Absolute Error**
* **MSE — Mean Squared Error**
* **RMSE — Root Mean Squared Error**

These metrics provide different ways of measuring prediction error.

### 11. Analyse Residuals

Residuals are examined to understand the errors produced by the regression model.

The notebook includes:

* Residual distribution
* Q-Q plot

These provide basic diagnostic checks for the regression model.

---

## Technologies Used

| Tool             | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming language      |
| Pandas           | Data manipulation         |
| NumPy            | Numerical operations      |
| Matplotlib       | Data visualization        |
| Seaborn          | Statistical visualization |
| Scikit-learn     | Machine learning          |
| SciPy            | Statistical analysis      |
| Jupyter Notebook | Analysis environment      |

---

## What I Practiced

Through this project, I practiced:

* Loading datasets with Pandas
* Inspecting and understanding tabular data
* Exploratory Data Analysis
* Correlation analysis
* Data visualization
* Selecting features and a target variable
* Splitting data into training and testing sets
* Training a Linear Regression model
* Interpreting regression coefficients
* Generating predictions
* Evaluating model performance
* Performing basic residual diagnostics

---

## Project Structure

```text
ecommerce-customers-linear-regression/
│
├── ecommerce_customers_linear_regression.ipynb
│
├── data/
│   └── Ecommerce Customers
│
└── README.md
```

---

## Level

**Beginner / Practice Project**

This project is intended for learners who are beginning to work with **Python, data analysis, and machine learning**.

The notebook includes explanations throughout the workflow so that the analysis can be followed step by step.

---

## Future Improvements

As my machine-learning skills develop, I can extend this project by exploring:

* Cross-validation
* Additional model evaluation techniques
* Feature engineering
* Regularized regression
* Comparing multiple regression models
* More detailed regression diagnostics
* Hyperparameter experimentation

---

## Dataset Attribution

Dataset provided through Kaggle:

**Linear Regression E-commerce Dataset**
[Kaggle Dataset Page](https://www.kaggle.com/datasets/kolawale/focusing-on-mobile-app-or-website?utm_source=chatgpt.com)

This repository uses the dataset for educational and practice purposes.
