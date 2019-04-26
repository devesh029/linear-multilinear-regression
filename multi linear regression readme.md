 Multiple Linear Regression using Python

It is the basic and commonly used type for predictive analysis. 

It is a statistical approach to modeling the relationship between a dependent variable and a given set of independent variables.

When more then one independent variable is invovled than we can consider it as multi-linear regression

Concept is same as that of linear regression

Equation of multi linear regression just have multiple slopes as coefficient of Independent Variables as compared to 

Simple linear regression(SLR).equation goes like this --> Y = m1*X1 + m2*X2 +.....+ Mn*Xn + c(intercept).intercept is only one like in SLR

And as compared to SLR here in MUlti linear regression there are few more assumptions before fitting the model on the dataset.

Data should follow this assumptions in order to work properly for this algorithm

Assumptions of regression model are as follows:


         1.)Linearity                 : The relationship between dependent and independent variables should be linear.
        
         2.)Homoscedasticity          : Constant variance of the errors should be maintained.
         
         3.)Multivariate normality    : Multiple Regression assumes that the residuals are normally distributed.
                                        or data should be of normal distribution
         
         4.)Lack of Multicollinearity : It is assumed that there is little or no multicollinearity in the data
         
    In Multiple Regression Model we use a lot of categorical data. Using Categorical Data is a good method to include 
    non-numeric data into respective Regression Model. Categorical Data refers to data values which represent categories-data 
    values with fixed and unordered number of values, for instance, gender(male/female). In the regression model, 
    these values can be represented by Dummy Variables.
    But right now i am going to use one inbuilt dataset in Python 3 which is known as boston house pricing 
    we will look at the dataset .its data types,are there any null values ,we will perform eda analysis on data and 
    check the relevant column for our model to avoid situations like underfitting or overfitting
    i will share my python file now ,it have description how i have worked on the dataset
