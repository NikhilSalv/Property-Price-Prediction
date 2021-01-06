# House-Price-Prediction
 Prediction of property prices is becoming increasingly important and beneficial. Property prices are a good indicator of both the overall market condition and the economic health of a country. In this project, we will build a Linear Regression model predict selling price of the property.

- # From a technical point of view, the main aspects of python covered throughout the notebook are:

data manipulation: pandas, numpy,Linear Regression
modeling: sklearn
class definition: Logistic Regression



- # Data Dictionary
The initial dataset has 1459 rows and 81 variables. But after general observations, we found that there are soe columns which have missing values more than 50% of the total number of observations. Hence, we decide to drop those columns.
We perform the Exploratory Analysis on the remaining columns by replacing the missing values with mean, in case of numeric data and replacing the same with the mode in case of categorical data. 
- # Label Encoding.
From sklearn.preprocessing , we are going to use Label Encoding, to convert the categorical data into numeric form. 
- # Model building
After completing the EDA, we will do random sampling using train test split and perform the Linear Regression on the dataset. 
- # The evaluation metrics of the prediction are as follows.
Root Mean Square Error = 136.722
Mean Absolute Percentage Error = 11.53
Accuracy = 88.46 %
