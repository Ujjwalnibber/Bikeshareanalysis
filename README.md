**Problem statement**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens
the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of 
rental bikes.  
**Project Summary**

In this project I have done analysis on data set available from bikes. I have started by importing important libraries and thren mounting drive followed by loading the data set. I have used various graphical and non graphical ways to do analysis.

As a data analyst one spends 60%-70% of time cleaning data, this steps is most cruical. We shall make relevant changes to dataset in this step. I have drawn all conclusions with help of different types of charts like scatter plot,bar charts , pie charts. In Categorical Variable and Univariate analysis indiviual column/variable has been picked up and analysis has been made using graphical and non graphical method,followed by Bivariate Analysis.I had taken each column and analyzerd the demand of bike according to it, for eg: the demand of bike according to hour , month, rainfall,snowfall ,visibility and other factors listed in the coulmns.

Further the data types have bben converted into relevant data tupes for better analysis,had checked for presence of null values,duplicate values. Outliers have been handled too and null values created due to dropping of outliers have been further treated by imputing them wit median value of respective column. The skewness of our dependent variab;e is treated by using square root method. The resultant graph is less skewed and free from outliers.

Featuring of the variables have been done as itv is pre - requisite to do and also the relation of numerical variables with the dependent variable has been done graphically to analyse their relation.

Once done we shall start splitting the dataset into two parts : dependent variables(X) and independent variable(Y).Then furher split your dataset into training and testing dataset.I shall be using various metrics to compare the output and find the best values that satisfy or for which cost function is lowest.I shall use GridSearchCV to choose our alpha values. We shall then implement regression model and then once done I would use LASSO AND RIDGE regrsssion to futher better the outputs.

At the end some conclusion have been drawn to gain insights and also important factor influencing the demand has been listed.

**Conclusion**


Most number of bikes are rented in the Summer season and the lowest in the winter season.

Over 96% of the bikes are rented on days that are considered as No Holiday.

Most number of bikes are rented in the temperature range of 15 degrees to 30 degrees.

Most number of bikes are rented when there is no snowfall or rainfall.

Majority of the bikes are rented for a humidity percentage range of 30 to 70. The highest number of bike rentals have been done in the 18th hour, i.e 6pm, and morning 8am

Most of the bike rentals have been made when there is high visibility.

Results from ML models:

Lasso Regression(L1 regularization) is the worst performing model with an r2 score of 0.4264.

Temperature and Hour are the two most important factors according to all the models.
