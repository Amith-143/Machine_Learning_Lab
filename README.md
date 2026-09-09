# Weekly Data Learning Notes

This repository contains my completed weekly Google Colab notes and practice work as I learn Python tools for data analysis and machine learning. Each week, I add the notebook I completed, along with the exercises and small projects covered in that week's lab.

The goal is to build a clear record of my learning, revisit important concepts, and track my progress over time.

## Contents

- [Repository Structure](#repository-structure)
- [Week 1: NumPy](#week-1-numpy)
- [Week 2: Pandas](#week-2-pandas)
- [Week 3: Data Preprocessing](#week-3-data-preprocessing)
- [Week 4: Statistics & EDA](#week-4-statistics--eda)
- [Week 5: Linear & Polynomial Regression](#week-5-linear--polynomial-regression)
- [Learning Goals](#learning-goals)
- [Future Updates](#future-updates)

## Repository Structure

The repository is organized by week. Each weekly folder or notebook includes the completed Colab notes, examples, exercises, and practice projects covered during that week's lab.

```text
weekly-data-learning-notes/
├── Week-01-NumPy/
│   └── completed_numpy_notes.ipynb
├── Week-02-Pandas/
│   └── completed_pandas_notes.ipynb
├── Week-03-Data-Preprocessing/
│   └── completed_data_preprocessing_notes.ipynb
├── Week-04-Statistics-EDA/
│   └── completed_statistics_eda_notes.ipynb
├── Week-05-Linear-Polynomial-Regression/
│   └── completed_linear_polynomial_regression_notes.ipynb
└── README.md
```

> File and folder names may be adjusted to match the notebooks in this repository.

## Week 1: NumPy

The first week's completed notes focus on **NumPy**. NumPy is a Python library used for working with arrays and numerical data.

This notebook documents my practice and understanding of the NumPy material from the lab.

## Week 2: Pandas

The second week's completed notes focus on **Pandas**, a Python library for working with structured and tabular data using DataFrames.

The Pandas lab includes practice with:

- Loading and inspecting data
- Selecting and filtering rows and columns
- Sorting data
- Creating new columns
- Cleaning data
- Grouping and aggregating data with `groupby()`
- Merging DataFrames
- Creating visualizations
- Exporting data to CSV files
- An image metadata mini-project
- A word-frequency mini-project

## Week 3: Data Preprocessing

The third week's completed notes focus on **Data Preprocessing**, which is the process of converting raw data into a form that can be effectively used by machine learning models.

The Data Preprocessing lab includes practice with:

- Handling missing data
- Dropping missing values when appropriate
- Filling missing values using mean, median, and mode
- Group-wise missing-value imputation
- Label encoding for binary and ordinal categorical variables
- One-hot encoding for categorical variables without a natural order
- Min-max feature scaling
- Standardization
- Understanding the effect of different feature scales on machine learning algorithms
- Detecting outliers using the IQR method
- Handling outliers using capping (winsorization)
- Splitting data into training and testing sets
- Understanding `test_size` and `random_state`
- Image pixel normalization from 0–255 to 0–1
- Resizing images to a consistent shape
- Text cleaning and tokenization
- Converting words into numerical IDs
- Understanding the limitations of direct word-to-ID encoding

The notebook also includes small practice exercises and mini-projects for **image preprocessing** and **text preprocessing**.

## Week 4: Statistics & EDA

The fourth week's completed notes focus on **Statistics and Exploratory Data Analysis (EDA)**. This lab focuses on using statistical methods and visualizations to understand datasets before building machine learning models.

The Statistics & EDA lab includes practice with:

- Descriptive statistics
- Mean and median
- Variance and standard deviation
- Understanding data spread
- Skewness and distribution shape
- Interpreting positive, negative, and near-zero skewness
- Visualizing distributions using histograms
- Detecting potential outliers using boxplots
- Understanding correlation between numerical variables
- Interpreting positive, negative, and near-zero correlation
- Understanding correlation strength
- Distinguishing correlation from causation
- Understanding non-linear relationships and why correlation may not detect them
- Hypothesis testing
- Comparing group means using a t-test
- Understanding and interpreting p-values
- Statistical significance and the 0.05 significance level
- Computing and interpreting confidence intervals
- Applying statistical analysis to image data
- Calculating image brightness statistics
- Correlation between image brightness and color-channel values
- Understanding the limitations of statistical tests with very small image samples
- Word-frequency analysis
- Understanding Zipf's Law and right-skewed word-frequency distributions
- Measuring vocabulary diversity using `diversity_ratio`
- Comparing sentence length with unique-word counts

The notebook also includes reflection questions and practice exercises designed to connect statistical analysis with **data preprocessing and machine learning**.

## Week 5: Linear & Polynomial Regression

The fifth week's completed notes focus on **Linear Regression and Polynomial Regression**, including model evaluation, regularization, cross-validation, Gradient Descent, and regression diagnostics.

The Linear & Polynomial Regression lab uses a **Cars24 used-car price dataset** to demonstrate how regression models can be built and evaluated step by step.

The lab includes practice with:

- Data preparation for regression
- Encoding categorical variables using mean target encoding
- Feature scaling
- Train-test splitting
- Simple Linear Regression
- Multiple Linear Regression
- Understanding coefficients and intercepts
- Making predictions with regression models
- R² score
- Adjusted R²
- Polynomial Regression
- Polynomial features such as `x²`, `x³`, and higher degrees
- Understanding polynomial degree
- Underfitting
- Overfitting
- Bias-Variance tradeoff
- Ridge Regression (L2 regularization)
- Lasso Regression (L1 regularization)
- Elastic Net regularization
- Understanding regularization strength (`alpha`)
- Hyperparameter tuning
- Choosing polynomial degree and regularization strength
- Train, validation, and test sets
- Cross-Validation
- K-Fold Cross-Validation
- Implementing Linear Regression from scratch
- Gradient Descent
- Learning rate and iterations
- Understanding why feature scaling improves Gradient Descent
- Comparing `sklearn` and `statsmodels`
- Ordinary Least Squares (OLS)
- Regression coefficients and p-values
- Confidence intervals
- Checking Linear Regression assumptions
- Multicollinearity
- Variance Inflation Factor (VIF)
- Residual analysis
- Residual normality
- Homoskedasticity
- Heteroskedasticity
- Goldfeld-Quandt test

The notebook also includes small synthetic examples to demonstrate **polynomial regression and regularization**, allowing the effect of model complexity and overfitting to be observed clearly.

## Learning Goals

Through these weekly notes and practice exercises, I am working to:

- Strengthen my Python programming skills
- Understand how to work with arrays, tables, and datasets
- Practice organizing, cleaning, and analyzing data
- Understand how raw data is prepared for machine learning
- Build confidence using NumPy and Pandas
- Learn important data preprocessing techniques
- Understand how categorical and numerical data are transformed
- Practice preprocessing image and text data
- Understand fundamental statistical concepts
- Perform exploratory data analysis using statistics and visualizations
- Interpret distributions, correlations, and statistical tests
- Understand regression and prediction problems
- Build and evaluate Linear Regression models
- Understand Polynomial Regression and model complexity
- Recognize underfitting and overfitting
- Learn regularization techniques such as Ridge, Lasso, and Elastic Net
- Understand Cross-Validation and model selection
- Understand Gradient Descent and how regression works internally
- Learn how to check Linear Regression assumptions
- Understand how statistical analysis supports machine learning decisions
- Keep a portfolio of my completed learning work

## Future Updates

New completed Colab notebooks will be added each week as I continue learning. Future notes may cover additional Python, data analysis, visualization, machine learning, deep learning, or related topics.

## How to Use This Repository

Open any `.ipynb` file in GitHub to preview it, or open it in Google Colab to run the code and explore the notes interactively.

---

This repository is a personal learning record and will grow as I complete more weekly labs.
