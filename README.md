## Welcom to Python and machine learning course

This repository is created by [Amir Mardan](https://amirmardan.github.io/) to maintain and preview the contents for a Python and machine learning course prepared for Amirkabir University of Technology, Tehran, Iran. Please contact me via my email (mardan.amir.h@gmail.com) for your lovely feedback and suggestions.

---
**NOTE**

I will push new contents weekly

---
# [1. Introduction to Python](https://github.com/AmirMardan/ml_course/blob/main/1_intro_to_python/0_intro_to_python.ipynb)
## 1.1 General programming
- An introduction
- Required tools
- Variables and data types
    - Numbers in Python
    - Strings in Python
    - Booleans in Python
    - List in Python
    - Dictionary in Python
- Operators
    - Comparison operators
    - Logical operators
    - Membership operators
    - Bitwise operators
- Control flow
    - `if` statements
    - `match` statements
    - `for` statements
    - `while` statements

## [1.2 Modular programming](https://github.com/AmirMardan/ml_course/blob/main/1_intro_to_python/1_modular_programming.ipynb)
- Functions
- `Lambda` functions
- Built-in functions
    - `map` function
    - `filter` function
    - `enumerate` function
    - `zip` function
- Classes / objects

# [2. Introduction to NumPy](https://github.com/AmirMardan/ml_course/blob/main/2_numpy/0_intro_to_numpy.ipynb)
- Creating a NumPy array
    - Creating arrays from lists
    - Special arrays
- Attributes of arrays
- Data Selection
    - Array indexing
    - Array slicing
    - Array view vs copy
    - Conditional selection
- Array manipulation
    - Shape of an array
    - Joining arrays
    - Splitting of arrays
- Computation on NumPy arrays
- Aggregations
    - Summation
    - Minimum and maximum
    - Variance and standard deviation
    - Mean and median
    - Find index

# 3. Data Manipulation with Pandas
## [3.1 Introduction to pandas](https://github.com/AmirMardan/ml_course/blob/main/3_pandas/0_intro_to_pandas.ipynb)
- Introducing Pandas objects
    - The pandas `Series` object
    - The pandas `DataFrame` object
- Data indexing and selection
    - Data selection in Series
    - Data selection in DataFrame
- Handling missing data
    - Detecting the missing values
    - Dealing with missing values
- IO in pandas

## [3.2 Data manipulation in using pandas](https://github.com/AmirMardan/ml_course/blob/main/3_pandas/1_data_manipulation_using_pandas.ipynb)
- Basic operations in pandas
- Combining datasets
    - Concat
    - Merge
    - Join
- Aggregation
- `Groupby`
- Vectorized string

# 4 Visualization

## [4.1 Matplotlib](https://github.com/AmirMardan/ml_course/blob/main/4_visualization/0_matplotlib.ipynb)
- Basic matplotlib
    - Simple matplotlib
    - Subplots
    - Object-oriented method
- Different types of plot
    - Scatter plot
    - Bar plot
    - Histogram
    - Pie chart
    - Box Plot
    - Violin plot
- Images with matplotlib
- Animation using matplotlib
    - Live graph with matplotlib
    
## [4.2 Seaborn](https://github.com/AmirMardan/ml_course/blob/main/4_visualization/1_seaborn.ipynb)
- Relational plots
- Distribution plots
    - `displot`
    - `jointplot`
    - `pairplot`
- Categorical plots
    - Categorical scatter plots
    - Categorical distribution plots
    - Categorical estimate plots
- Regression plots
- FacetGrid
- Customization
    - Style and theme
    - Colors

# 5 Data Analysis and Processing

## [5.1 Exploratory data analysis (EDA)](https://github.com/AmirMardan/ml_course/blob/main/5_data_analysis_processing/0_introduction_to_EDA.ipynb)
- Initial general assessment
- Basic analysis
- Missing data
- Outliers
- Correlation

## [5.2 Data preparation](https://github.com/AmirMardan/ml_course/blob/main/5_data_analysis_processing/1_intro_to_data_preparation.ipynb)

## [5.3 Data Cleaning](https://github.com/AmirMardan/ml_course/blob/main/5_data_analysis_processing/2_data_cleaning.ipynb)
- Initial general assessment
    - Rows with duplicated data
    - Columns with a single value
- Outliers
    - Standard deviation method
    - Interquartile range method
- Missing data
    - Remove rows with missing values
    - Filling missing values

## [5.4 Data Transforms](https://github.com/AmirMardan/ml_course/blob/main/5_data_analysis_processing/3_data_transform.ipynb)
- Scaling numerical data
    - Data normalization
    - Data standardization
    - Robust scaling
- Encode categorical data
    - Ordinal Encoding
    - One Hot Encoding
    - Dummy Encoding
- How to make distribution more Gaussian
    - Box-Cox transform
    - Yeo-Johnson transform
    - Quantile transform

# 6 Classical Machine Learning

## [6.1 Introduction to Machine Learning](https://github.com/AmirMardan/ml_course/blob/main/6_classical_machine_learning/0_Intro_to_ML.md)

## [6.2 Introduction to Scikit-Learn](https://github.com/AmirMardan/ml_course/blob/main/6_classical_machine_learning/1_intro_to_sklearn.ipynb)
- Data presentation
- Models in Scikit-learn
    - Simple linear regression example
    - Simple classification example
    - Simple dimensionality reduction example
    - Simple clustering example
- Hyperparameters and model validation
    - Cross validation
    - Finding the best model
    - Grid Search

## [6.3 Regression 1](https://github.com/AmirMardan/ml_course/blob/main/6_classical_machine_learning/2_regression_1.ipynb)
- Ordinary Linear Regression
- Linear Regression With Regularization
    - Ridge Regularization
    - Lasso Regularization
    - Combined Regularization
- A Linear Regression Project
    - Exploratory Data Analysis
    - Data Cleaning
    - Data Processing Pipeline
- Training and Evaluation
    - Training Curve

## [6.4 Classification 1](https://github.com/AmirMardan/ml_course/blob/main/6_classical_machine_learning/3_classification_1.ipynb)
- Logistic Regression
- Support Vector Machine
- Random Forest Classifier

## [6.5 Clustering 1](https://github.com/AmirMardan/ml_course/blob/main/6_classical_machine_learning/4_clustering_1.ipynb)
- k-Means Clustering
- Gaussian Mixture Models
- Evaluation Clustering Models

# 7. Fully Connected Neural Networks (FCNNs)

## [7.1 Introduction to TensorFlow](https://github.com/AmirMardan/ml_course/blob/main/7_fully_connected_nn/0_intro_to_tensorflow.ipynb)
- Graph and Session
    - Build and Perform a Graph
    - Gradient in TensorFlow
- Tensor types in TensorFlow
    - Constant
    - Variable
- Tensor Manipulation
    - Creating A Tensors
    - Creating Special Tensors
    - Shape Manipulation
    - Slicing
- Operators
    - Basic Arithmetic Operators
    - Comparison Operators
    - Logical And Bitwise Operators

## [7.2 Introduction To Fully Connected Neural Networks](https://github.com/AmirMardan/ml_course/blob/main/7_fully_connected_nn/1_intro_to_NN.ipynb)
- Neural Network From Scratch
- Neural Network With TensorFlow

