# BINARY-CLASSIFICATION-MODELING-USING-ALTERYX
Problem Statement: - 
Whether the hotel customer will redeem the yearly subscription or not ?
I have used Alteryx to develop Logistic Regression, Step wise Logistic Regression and Decision Tree Model to predict binary outcomes by analyzing the outcome’s relationship with one or more predictor variables.
Before starting applying the algorithms on the given hotel loyalty data set, I have created the estimation and validation sample.

![image](https://user-images.githubusercontent.com/16829371/33813030-7897217c-ddef-11e7-8cde-b1ec7244405c.png)

## 1.	Building Logistic Regression Model

![image](https://user-images.githubusercontent.com/16829371/33813053-aa0e787c-ddef-11e7-9b9d-b8423f2efecd.png)

![image](https://user-images.githubusercontent.com/16829371/33813054-ad4ac86a-ddef-11e7-8971-d15fda724e52.png)

The above process is bit of a manual process which requires selecting and deselecting variables of interest. 
I will use Stepwise Logistic Regression Model to automate the above process.

## 2.	Logistic Regression - Stepwise
For building Stepwise Logistic Regression Model I have selected all the possible variables. The Stepwise Regression tool in Alteryx automatically figures out all the possible variables it can calculate first and it takes this list of possible variables from the Logistic Regression Tool as an output.
After running the stepwise logistic regression model, we will be able to reduce much of the unnecessary variables.

![image](https://user-images.githubusercontent.com/16829371/33813138-13d112ba-ddf0-11e7-852b-a31289e6e4a7.png)

## 3.	Decision Tree Model Using Alteryx
