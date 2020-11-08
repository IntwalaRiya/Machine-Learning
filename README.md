# Machine-Learning

## Linear Regression
### Linear Regression: 
    It is all about a linear approach among one scalar resource (i.e. dependent variable) and one or more explanatory variables (i.e. independent variables). Here explanatory variables need to be continuous.

### Scalar Response: 
    By scalar response also known as dependent variable, it means we get one random variable from predictor and dependency on other variables. We call it Scalar response because we get a predicted scalar value from predictor.

### Explanatory Variables: 
    By explanatory variable, it means there are more than one variable which are independent of other variables. Also known as Independent variable or Predict variable. We call it explanatory as for scientist it gives them explanation for the variations in response variable from predictor.
If there are more than one explanatory variables, then it is called Multiple Linear Regression.

## Types of Linear Regression:

   ### 1.	Simple Linear Regression: 
    -> In Simple Linear Regression, we try to find the relationship between a single independent variable (input) and a corresponding dependent variable (output).

   ### 2.	Multiple Linear Regression:
    ->	In Multiple Linear Regression, we try to find the relationship between 2 or more independent variables (inputs) and the corresponding dependent variable (output). 

## Cost Function:
		![Cost Function](https://media.geeksforgeeks.org/wp-content/uploads/LR-cost-function-2.jpg) 
Cost function(J) of Linear Regression is the Root Mean Squared Error (RMSE) between predicted Y value (PRED) and true Y value (Y).

## Gradient Descent
### Gradient Descent: 
		![Gradient Descent](https://media.geeksforgeeks.org/wp-content/uploads/LR-cost-function-1.jpg)
    It is used to update coefficient of X in such a way that it reduces cost function. It will start with random values of coefficient of X, and then iteratively update it till it reaches the minimum Cost.
 

## Logistics Regression
  ### Logistic Regression: 
      It is also one of the statistical methods. It is used to predict binary variable Y from one or more response variable X. Here response variables can be either of continuous or categorical.

## Types of Logistic Regression

   ### 1.	Binary Logistic Regression: 
        ->	The categorical response has only two 2 possible outcomes. Example: Spam or Not
   ### 2.	Multinomial Logistic Regression:
        -> Three or more categories without ordering. Example: Predicting which food is preferred more (Veg, Non-Veg, Vegan)
   ### 3.	Ordinal Logistic Regression:
        ->	Three or more categories with ordering. Example: Movie rating from 1 to 5

## Cost Function:
		![Cost Function](https://i.stack.imgur.com/XbU4S.png) 	
		
## Linear Regression Vs Logistic Regression:
  	->	Linear regression is used for predicting the continuous dependent variable using a given set of independent features, whereas Logistic Regression is used to predict the categorical. 
  	->	Linear regression is used to solve regression problems, whereas logistic regression is used to solve classification problems.
