# Weekly Data Learning Notes

This repository contains my completed weekly Google Colab notes and practice work as I learn Python tools for data analysis and machine learning. Each week, I add the notebook I completed, along with the exercises, concepts, reflection questions, and small projects covered in that week's lab.

The goal is to build a clear record of my learning, revisit important concepts, and track my progress over time.

## Contents

- [Repository Structure](#repository-structure)
- [Week 1: NumPy](#week-1-numpy)
- [Week 2: Pandas](#week-2-pandas)
- [Week 3: Data Preprocessing](#week-3-data-preprocessing)
- [Week 4: Statistics & EDA](#week-4-statistics--eda)
- [Week 5: Linear & Polynomial Regression](#week-5-linear--polynomial-regression)
- [Week 6: Polynomial Regression & Regularization](#week-6-polynomial-regression--regularization)
- [Week 7: KNN & Distance Measures](#week-7-knn--distance-measures)
- [Learning Goals](#learning-goals)
- [Future Updates](#future-updates)
- [How to Use This Repository](#how-to-use-this-repository)

## Repository Structure

The repository is organized by week. Each weekly folder contains the completed Colab notebook, examples, exercises, reflection questions, and practice projects covered during that week's lab.

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
├── Week-06-Polynomial-Regularization/
│   └── completed_polynomial_regularization_notes.ipynb
├── Week-07-KNN-Distance-Measures/
│   └── completed_knn_distance_measures_notes.ipynb
└── README.md
Week 1: NumPy
The first week's completed notes focus on NumPy. NumPy is a Python library used for working with arrays and numerical data.
This notebook documents my practice and understanding of the NumPy material from the lab.
Week 2: Pandas
The second week's completed notes focus on Pandas, a Python library used for data manipulation and analysis.
The notebook covers:
- Loading and inspecting datasets using Pandas
- Understanding DataFrames and Series
- Selecting rows and columns
- Filtering data using conditions
- Sorting data
- Creating new columns
- Cleaning and organizing datasets
- Handling and analyzing tabular data
- Grouping data using groupby()
- Aggregating grouped data
- Merging and combining DataFrames
- Creating basic data visualizations
- Exporting processed data to CSV files
- Working with image metadata
- Image metadata mini-project
- Word-frequency mini-project
The exercises helped me understand how raw datasets can be explored, organized, transformed, and prepared for further analysis.
Week 3: Data Preprocessing
The third week's completed notes focus on Data Preprocessing.
The notebook covers:
- Identifying missing data
- Removing missing values using dropna()
- Filling missing values using fillna()
- Mean, median, and mode imputation
- Group-wise imputation
- Label encoding
- Binary and ordinal categorical encoding
- One-hot encoding
- Min-Max scaling
- Standardization
- Understanding the effect of feature scales
- Detecting outliers using the IQR method
- Winsorization
- Train-test splitting
- Understanding test_size
- Understanding random_state
- Image pixel normalization
- Converting pixel values from 0–255 to 0–1
- Image resizing
- Text cleaning
- Tokenization
- Converting text into numerical IDs
- Limitations of direct word-to-ID conversion
- Image preprocessing mini-project
- Text preprocessing mini-project
This week helped me understand how raw data can be cleaned and transformed into a suitable format for machine learning models.
Week 4: Statistics & EDA
The fourth week's completed notes focus on Statistics and Exploratory Data Analysis (EDA).
The notebook covers:
- Descriptive statistics
- Mean and median
- Variance and standard deviation
- Understanding data spread
- Skewness
- Positive, negative, and near-zero skewness
- Histograms
- Boxplots
- Correlation
- Understanding correlation strength
- Correlation does not imply causation
- Limitations of correlation for non-linear relationships
- Hypothesis testing
- T-test
- P-values
- Significance level of 0.05
- Confidence intervals
- Image brightness statistics
- Image color statistics
- Limitations of using small image samples
- Word-frequency analysis
- Zipf's law
- diversity_ratio
- Sentence length
- Number of unique words
- Exploratory analysis of image and text data
The reflection and practice work connected statistical analysis with data preprocessing and machine learning.
Week 5: Linear & Polynomial Regression
The fifth week's completed notes focus on Linear Regression, Polynomial Regression, Model Evaluation, and Regression Analysis.
The notebook covers:
- Data preparation for regression
- Working with the Cars24 used-car price dataset
- Mean target encoding
- Feature scaling
- Train-test splitting
- Simple Linear Regression
- Multiple Linear Regression
- Understanding coefficients and intercepts
- Making predictions
- R² score
- Adjusted R²
- Polynomial Regression
- Polynomial features such as x² and x³
- Higher-degree polynomial features
- Understanding polynomial degree
- Comparing different polynomial degrees
- Model complexity
- Underfitting
- Overfitting
- Bias-variance tradeoff
- Comparing training and testing performance
- Ridge Regression
- L2 regularization
- Lasso Regression
- L1 regularization
- Elastic Net
- Understanding alpha
- Testing different regularization strengths
- Small and large regularization values
- Train, validation, and test datasets
- Cross-validation
- K-fold cross-validation
- Linear Regression from scratch
- Gradient Descent
- Learning rate
- Number of iterations
- Importance of scaling for Gradient Descent
- Comparing Scikit-learn and Statsmodels
- Ordinary Least Squares (OLS)
- Coefficients and p-values
- Confidence intervals
- Regression assumptions
- Multicollinearity
- Variance Inflation Factor (VIF)
- Residual analysis
- Normality of residuals
- Homoskedasticity
- Heteroskedasticity
- Goldfeld-Quandt test
- Synthetic regression examples
The exercises helped me understand how regression models are built, evaluated, improved, and interpreted.
Week 6: Polynomial Regression & Regularization
The sixth week's completed notes focus on Polynomial Regression, Regularization, Bias-Variance Tradeoff, and Hyperparameter Tuning.
The notebook covers:
- Polynomial feature generation
- Polynomial Regression
- Understanding polynomial degree
- Comparing different polynomial degrees
- Model complexity
- Underfitting
- Overfitting
- Bias-variance tradeoff
- Comparing training and testing performance
- Finding the degree with the best test performance
- Ridge Regression
- L2 regularization
- Understanding alpha
- Testing different regularization strengths
- Effect of small and large alpha values
- Lasso Regression
- L1 regularization
- Elastic Net
- Comparing different regularization techniques
- Hyperparameter tuning
- Model generalization
Synthetic examples were used to demonstrate how polynomial degree and regularization affect model complexity, bias, variance, underfitting, and overfitting.
Week 7: KNN & Distance Measures
The seventh week's completed notes focus on K-Nearest Neighbors (KNN), Distance Measures, Feature Scaling, and Classification.
The notebook covers:
- Understanding K-Nearest Neighbors (KNN)
- Euclidean distance
- Manhattan distance
- Minkowski distance
- Implementing and comparing distance measures
- Train-test splitting
- Stratified train-test splitting
- Feature scaling using StandardScaler
- Understanding why scaling is important for distance-based algorithms
- KNN classification using the Iris dataset
- Choosing the value of K
- Evaluating KNN using accuracy
- Confusion matrix
- Comparing K=1, K=5, and larger values of K
- Understanding K performance
- Bias-variance tradeoff in KNN
- Overfitting and underfitting
- K-value sweep from 1 to 30
- Selecting a suitable K using test accuracy
- Hand-computed KNN distances
- Ranking nearest neighbors
- Classifying a new data point
- KNN classification using the handwritten digits dataset
- Working with flattened image data
- Classifying handwritten digits
- Visualizing incorrect predictions
- Text classification using KNN
- Creating a vocabulary
- Bag-of-words representation
- Text vectorization
- KNN for text classification
- Limitations of the bag-of-words approach
- Understanding the importance of sample size
The exercises helped me understand how KNN uses distances and neighboring data points to perform classification, and why feature scaling and the choice of K are important.
The digits and text mini-projects also showed how the same KNN concept can be applied to different types of data such as numerical features, images, and text.
Learning Goals
Through these weekly labs, my main learning goals are:
- Strengthen my Python programming skills
- Understand NumPy arrays and numerical operations
- Work with tables and datasets using Pandas
- Learn how to organize, clean, and analyze data
- Understand how raw data is prepared for machine learning
- Learn data preprocessing techniques
- Handle categorical and numerical features
- Apply transformations to image and text data
- Understand basic statistics
- Perform Exploratory Data Analysis (EDA)
- Analyze distributions and correlations
- Perform basic hypothesis testing
- Understand regression and prediction
- Learn Linear Regression
- Learn Polynomial Regression
- Understand model complexity
- Understand underfitting and overfitting
- Understand the bias-variance tradeoff
- Learn regularization techniques such as Ridge, Lasso, and Elastic Net
- Understand Cross-Validation and model selection
- Understand Gradient Descent
- Understand regression assumptions
- Learn distance-based classification
- Understand K-Nearest Neighbors (KNN)
- Implement different distance measures
- Understand the importance of feature scaling
- Evaluate classification models using accuracy and confusion matrices
- Understand how K affects bias and variance
- Apply KNN to numerical, image, and text data
- Understand the limitations of bag-of-words text representation
- Understand how sample size affects model reliability
- Build a strong foundation for future machine learning projects
Future Updates
New completed Colab notebooks will be added each week as I continue learning. Future notes may cover additional Python, data analysis, visualization, machine learning, deep learning, or related topics.
How to Use This Repository
Open any .ipynb file in GitHub to preview it, or open it in Google Colab to run the code and explore the notes interactively.
This repository is a personal learning record and will grow as I complete more weekly labs.
