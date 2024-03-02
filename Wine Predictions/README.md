# Project Overview


- **Importing libraries**: The notebook imports pandas, numpy, seaborn, matplotlib, and scipy as libraries for data manipulation, visualization, and statistics.
- **Loading data**: The notebook reads a CSV file named 'winequality-red.csv' into a pandas dataframe called df. The dataframe has 12 columns, including 11 features and 1 target variable (quality).
- **Exploratory data analysis**: The notebook performs some basic descriptive statistics, such as mean, standard deviation, min, max, etc. on the dataframe. It also shows the first five rows of the dataframe and the unique values of the quality column. It checks for missing values and finds none. It calculates the correlation matrix of the dataframe and plots it as a heatmap.
- **Outlier detection**: The notebook uses the z-score method to identify and remove outliers from the dataframe. It creates a new dataframe called new_df that has 1451 rows and 12 columns, after dropping 148 rows that had z-scores greater than 3.

- **Model**: Then we made a model using RandomForestClassifier with a accuracy of 75%
