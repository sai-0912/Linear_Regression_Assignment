# Linear Regression Assignment
> Multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* Introduction
* Python libraries
* The problem statement
* Independent and dependent variable
* Regression metrics for model performance i. RMSE ii. R2 Score
* Residual analysis

<!-- You can include any other section that is pertinent to your problem -->

## Introduction
* In this project i have to build a multiple linear regression model for the prediction of demand for shared bikes.


## Python libraries
* I have Anaconda Python distribution installed on my system. It comes with most of the standard Python libraries I need for this project. The basic Python libraries used in this project are:-

* Numpy – It provides a fast numerical array structure and operating functions.

* pandas – It provides tools for data storage, manipulation and analysis tasks.

* Scikit-Learn – The required machine learning library in Python.

* Matplotlib – It is the basic plotting library in Python. It provides tools for making plots.





## The problem statement
* The aim of building a machine learning model is to solve a problem and to define a metric to measure model performance. So, first of all I have to define the problem to be solved in this project. As described earlier, the problem is to model and investigate the linear relationship between Sales and Advertising dataset for a dietary weight control product. I have used two performance metrics RMSE (Root Mean Square Value) and R2 Score value to compute our model performance.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Independent and dependent variable
* In this project, I refer Independent variable as Feature variable and Dependent variable as Target variable. These variables are also recognized by different names as follows: -

* Independent variable
  Independent variable is also called Input variable and is denoted by X. In practical applications, independent variable is also called Feature variable or Predictor variable. We can denote it as: -      Independent or Input variable (X) = Feature variable = Predictor variable

* Dependent variable
  Dependent variable is also called Output variable and is denoted by y. Dependent variable is also called Target variable or Response variable. It can be denote it as follows: -

* Dependent or Output variable (y) = Target variable = Response variable


## Residual analysis
* A linear regression model may not represent the data appropriately. The model may be a poor fit to the data. So, we should validate our model by defining and examining residual plots.

* The difference between the observed value of the dependent variable (y) and the predicted value (ŷi) is called the residual and is denoted by e. The scatter-plot of these residuals is called residual   plot.

* If the data points in a residual plot are randomly dispersed around horizontal axis and an approximate zero residual mean, a linear regression model may be appropriate for the data. Otherwise a non-     linear model may be more appropriate.

* If we take a look at the generated ‘Residual errors’ plot, we can clearly see that the train data plot pattern is non-random. Same is the case with the test data plot pattern. So, it suggests a 
  better-fit for a non-linear model.




<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
