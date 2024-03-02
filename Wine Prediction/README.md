

# Wine Quality Prediction

This project is about predicting the quality of wine based on various physicochemical properties. The dataset used in this project is the 'Wine Quality' dataset available on the UCI Machine Learning Repository.

## Project Structure

The project has the following structure:

- **Importing libraries**: Necessary Python libraries for data manipulation, visualization, and statistics are imported. These include pandas, numpy, seaborn, matplotlib, and scipy.

- **Loading data**: The 'winequality-red.csv' file is loaded into a pandas dataframe. This dataframe consists of 11 features and 1 target variable (quality).

- **Exploratory data analysis (EDA)**: Basic descriptive statistics are performed on the dataframe. This includes calculating the mean, standard deviation, min, max, etc. The first five rows of the dataframe are displayed along with the unique values of the quality column. The notebook also checks for missing values and finds none. A correlation matrix of the dataframe is calculated and visualized as a heatmap.

- **Outlier detection**: The z-score method is used to identify and remove outliers from the dataframe. A new dataframe is created, which has 1451 rows and 12 columns, after dropping 148 rows that had z-scores greater than 3.

- **Model**: A model is built using the RandomForestClassifier. The model achieves an accuracy of 75%.

## Conclusion

This project demonstrates the process of predicting wine quality using machine learning. The RandomForestClassifier model was able to achieve a reasonable accuracy of 75%. Future work could involve tuning the model parameters or trying different machine learning algorithms to improve the accuracy.
