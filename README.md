# Linear-Regression-Machine-Learning-Project

##### The data used to perform this project is [Solar Power Generation](https://www.kaggle.com/datasets/pythonafroz/solar-powe-generation-data) from Kaggle.

This Project used libraries like **pandas, numpy, sklearn, matplotlib** to perform operation on the dataset. 
>Pandas was used for data analysis, Numpy was used to convert selected columns into two dimensional, Sklearn was used to split data into train and test and Matplotlib was used to represent the sleected columns relation on the graph.

First, the data in csv format is converted into a dataframe. Then we had selected the required x and y columns to perform linear regression.
>y=m*x+c where m is the coefficient and c is the intercept

Then we used matplotlib to know the relation between the selected columns from the dataset. From the data *Radiation* and *SystemProduction* columns had been selected.

Using sklearn train_test_split function the data was split as train and test data.

Using numpy we converted the training data into two dimensional array.

From sklearn we imported LinearRegression Algorithm to perform the prediction on training data and testing data and check the similarity using graphs.

This is a beginner level project of Simple Linear Regression Machine Learning Algorithm.
