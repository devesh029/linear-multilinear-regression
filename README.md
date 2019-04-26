# Simple linear regression
Linear Regression is a machine learning algorithm based on supervised learning. 
It performs a regression task. Regression models a target prediction value based on independent variables.
It is mostly used for finding out the relationship between variables and forecasting. 
here "linear" means that relationship between Dependent Variable(DV) and Independent Variable(IV)
this technique finds best fi by findind best values of coefficient of independent variable and intercept value
linear regression equation --> Y(DV) = b1(intercept) + b2*X(IV)
This technique uses Cost Function it aims to predict Y value such that the error difference between predicted value(Ypred) and true value(Y) is minimum. So, it is very important to update the b1 and b2 values, to reach the best value that minimize the error between predicted y value (pred) and true y value (y).
We use Gradient Descent to update value of b1 and b2. Idea is to start with random b1 and b2 values and then iteratively updating the values, reaching minimum cost.
We are going to use an inbuilt dataset to apply this machine learning regression technique
In simple linear regression there is only one independent variable and one dependent variable that is why it is called simple linear regression
we are going to use simple dataset to know how can we apply these technique
we are going to use salary_data in which you will try to predict salary based on number of years of experience
