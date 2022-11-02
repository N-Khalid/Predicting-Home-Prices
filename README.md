## Group_4

## Selected topic

Predicting Home Prices

## Resources
* Data Sources: test.csv, train.csv, data_description.txt
* Software: Python 3.9.12, Jupyter Notebook 6.4.8, PgAdmin4 v6.8, https://app.quickdatabasediagrams.com/, Tableau, GitHub, Slack, VSCode v1.72.2

##  Reason we selected the topic

We want to investigate how different home features affect the price of a home in Ames, Iowa. The main features we would like to analyze would be:
  - number of bedrooms and bathrooms
  - year built
  - square footage 
  - if the home has heating/central air
  - if the home has a garage, and how many cars can fit in it
  
##  Description of our source of data

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

## Questions we hope to answer with the data

  - Based on key home features, how accurately can we predict the cost of a home?
  - Which feature affects the cost the most? What feature affects the cost the least?
  
##  Machine Learning

###  Preliminary Data Preprocessing

The goal of data preprocessing is to change our initial dataset into a cleaner dataset to assist in answering our questions. Our data preprocessing process is as follows:

- Make a copy of our initial dataset to use as the working dataset
- Identify what our dependent and independent variables will be
- Check if there are missing values or values that do not make sense within context of the dataset (ex. 0 or N/A for number of beds or bathrooms)
    
###  Preliminary Feature Engineering

### Splitting the Data

The dataset came prepared with train and test 

###  Model Choice

The model we decided to use is a multiple linear regression model. We decided to go with a supervised machine learning model because we are trying to predict a known dependent variable (sale price) with various independent variables that can all effect the sale price (lot size, type of road access to the property, year built, heating, central air, full bath, half bath, bedrooms, total rooms and garage size)

Limitations: 

- The size of the dataset can skew the analysis. If there are only a few datapoints, we may conclude that the weight of certain variables may be higher or lower than they really are. 

- Incomplete data can make us conclude things strictly based on whats presented in the dataset. If certain variables with high correlation are absent from the dataset meanwhile low correlation variables are present, we may conclude that our target value may be higher or lower than it really is.

Benefits: 

- We are able to identify the correlation between of one or more variables to our target variable and exactly how much each independent variable influences it.
- We are able to identify the outliers in our dataset. When we use this model we can see certain variables may not have as much influences as one may have thought and can potentially remove them. We can also find out that certain target variables may or may not be influenced the same way as other similar target variables.
  
## First Segment Deliverable

For the first segment of the final project, we created an initial presentation that details the main focus of our project, and our plans to work with the data. We also listed the main questions that we would like to answer as we work through the dataset. The README was updated with this draft, as seen below: 

![Screen Shot 2022-10-27 at 8.19.38 PM.png](https://github.com/N-Khalid/Predicting-Home-Prices/blob/Simran---Square-1/Screen%20Shot%202022-10-27%20at%208.19.38%20PM.png)

For our initial GitHub setup, we created four branches for each of the team members, and assigned our roles. The branches were named with the respective roles to create a space for each team member's work. 

![Screen Shot 2022-10-27 at 8.20.01 PM.png](https://github.com/N-Khalid/Predicting-Home-Prices/blob/Simran---Square-1/Screen%20Shot%202022-10-27%20at%208.20.01%20PM.png)

