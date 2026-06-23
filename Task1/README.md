# Task Objective

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Iris dataset to understand:

1. Data structure
2. Feature relationships
3. Statistical properties
4.Visual patterns between different flower species

The goal is to identify which features are most useful for distinguishing Iris flower species.

# Dataset Used

*Iris Dataset*

Source: Built-in dataset from seaborn
Total samples: 150 rows

Features:
 1. sepal_length
 2. sepal_width
 3. petal_length
 4. petal_width
 5. species (target variable)

This dataset contains three flower species:
1. Setosa
2. Versicolor
3. Virginica

# Tools & Libraries Used
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook

# Analysis Performed
*1. Data Exploration*
Checked dataset shape
Viewed column names
Used *.head()* for preview
Used *.info()* for data types and null values
Used *.describe()* for statistical summary

*2. Data Visualization*
1. Pairplot for overall feature relationships
2. Scatter plots for feature comparisons
3. Histograms for distribution analysis
4. Box plots for outlier detection

# Key Results & Findings
1. Petal length and petal width are the most important features
2. hey clearly separate all three species
3. Sepal features show overlapping distributions
4. Setosa species is easily separable from others
5. Versicolor and Virginica are closer but still distinguishable using petal features