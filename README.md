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

![image](https://user-images.githubusercontent.com/16829371/33813103-f372a394-ddef-11e7-876a-ef0a60d17b7e.png)
 
![image](https://user-images.githubusercontent.com/16829371/33813088-e3a2d84e-ddef-11e7-810c-b879f34b628c.png)

![image](https://user-images.githubusercontent.com/16829371/33813091-e72ca828-ddef-11e7-8407-0014a0f7b745.png)


## 4.	Comparing Logistic Regression Model with Decision Tree Model
On Comparing the Logistic Regression Model against Decision Tree Model, the accuracy of Logistic Regression is better as compared to Decision Tree Model.

![image](https://user-images.githubusercontent.com/16829371/33813205-64167d28-ddf0-11e7-91e3-9d6be6526a98.png)

![image](https://user-images.githubusercontent.com/16829371/33813209-6975a3b6-ddf0-11e7-9345-9e23259d8bb8.png)

![image](https://user-images.githubusercontent.com/16829371/33813212-6eff56b0-ddf0-11e7-8ab0-8fb94ec7c47c.png)

Result shows that the Logistic Regression Step Wise Model seems to perform better than the Decision Tree model.

## 5.	Scoring the Model
The model in this case Stepwise Logistic Regression is scored against a new dataset to make predictions. This dataset have all the predictor variable values, which are passed through the model to predict the unknown target variable value. The prediction will be a number between 0 and 1, representing the likelihood of positive outcome.

![image](https://user-images.githubusercontent.com/16829371/33813239-9a51c62c-ddf0-11e7-867d-8e320e5f8cdd.png)

![image](https://user-images.githubusercontent.com/16829371/33813244-a013ed92-ddf0-11e7-9a58-72fc7e96ca0c.png)

## 6.	Visualization

![image](https://user-images.githubusercontent.com/16829371/33813299-be9d4da8-ddf0-11e7-8371-9b2f0d5ea1f9.png)


