# LinearRegression_Python
The intentions of this Python Application was perform both simple and multiple linear regression on student performances.

About the data set
The data set was retrieved from a publically avaliable website known as Kaggle.com. 
The link to the data set: https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression.

According to Narayan (2023), the data set contains 10 000 records and due to the structure of the data set, it allowed for multiple factors to be investigated in-order to examine the influencial factors affecting the performance of students. 
The data set contains a total of six columns although, Narayan (2023) deems that the column named 'Performance Index' will serve as the target variable for the algorthms predictions. 
The remaining five columns are namely, 'Hours Studied', 'Previous Scores', 'Extracurricular Activities', 'Sleep Hours' and 'Sample Question Papers Practiced' (Narayan, 2023).

When divulging into the description of these columns, Narayan (2023) indicated that 'Hours Studied' column is used to represent the total number of hours each student spent studying; the 'Previous Scores' column retains the scores each student achieved in their previous tests; 
'Extracurricular Activities' is used to indicate whether a student partakes in other activities; the 'Sleep Hours' column is used to indicate the average number of hours a student attained each day; 
lastly, the 'Sample Question Papers Practiced' column is used to indicate the amount of practice each student recieved through sample question papers. 

The target column, 'Performance Index' is used to gauge the performance of each individual student, this column makes use of a specified range, it is from ten to one-hundred, where the lower the index value, the worse their performance although, 
the greater the value, the better the students performance. 

# Python Application Steps. 
The following list will serve as a breakdown for the flow of the application:

1. The application starts with the neccessary imports in-order to execute/compile the application.
2. The second step involved loading the data set into a dataframe. 
3. Upon loading the data set into a dataframe, the third step involved investigating the data/data exploration.
    - This involved printing the first and last five rows. 
    - Then checking if there are null values within the data set. 
    - Followed by counting the total number of rows in each column. 
    - Lastly, it involved displaying the data types of each feature.

4. The forth step was used for data preprocessing. 
    - A label encoder was used to transform the categorical elements into numerical values. 

5. The fifth step was used to create both a simple and heatmap correlation matrix of data sets features. 

6. Upon discovering the correlation scores between each feature, two simple linear regression models were created. 
    - It must be noted that in-order to evaluate both models, the target variable was kept constant, the 'Performance Index' column/feature.
    - The two columns scoring the highest correlations are 'Previous Scores' (0,92) and 'Hours Studied' (0,37).

7. The seventh step was to make use of data visualization techniques to visually interpret both simple linear regression models. 
8. Thereafter, both simple linear regression models underwent evaluation scoring metrics. 
    - Of the two simple linear regression models, the first model attained the best scores. 
    - The mean squared error (MSE) was still quite high however, the r-sqaured value was 0,841. Unlike the second simple linear regression model with an 
      MSE score of 321.81 and an r-squared value of 0.131. 

9. The following steps will involve making use of multi-linear regression. 

# Refrences.

Narayan, N. 2023. Student Performance (Multiple Linear Regression), 2023. Avaliable at: https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression. 