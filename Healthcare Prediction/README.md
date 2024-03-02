# Project Overview



- **Healthcare Diabetes Dataset Analysis**: This a  Jupyter notebook that performs an exploratory data analysis and predictive modeling on a healthcare diabetes dataset using Python libraries such as pandas, numpy, matplotlib, seaborn, and sklearn.
- **Dataset Description**: The dataset contains 768 observations and 9 variables, including 8 features (such as pregnancies, glucose, blood pressure, skin thickness, insulin, BMI, diabetes pedigree function, and age) and 1 target (outcome, indicating whether the person has diabetes or not).
- **Data Visualization**: This project displays various plots to examine the distribution, correlation, and relationship of the variables, such as histograms, pair plots, scatter plots, and heat maps   .
- **Machine Learning Models**: This project applies five different machine learning models to predict the outcome variable based on the features, such as logistic regression, decision tree, random forest, support vector classifier, and KNN model    . It also evaluates the performance of each model using metrics such as accuracy, f1-score, average precision, and AUC    .

Based on the results, the best model for this dataset is the **random forest classifier**, which has the highest accuracy score (93.23%), f1-score (89.96%), average precision (95.75%), and AUC (97.88%) among all the models. The support vector classifier also has a high accuracy score (92.32%) and f1-score (87.63%), but it has a low test score (61.69%), indicating that it is overfitting the training data. The other models have lower accuracy and f1-scores, ranging from 76.64% to 82.03% and 62.27% to 71.17%, respectively.   .
