polynomial regression model on a simple data lacking linear relation:

               When the dependent variable and independent variables does not have a
  linear relationship the polynomial linear regression can be used if you
  suspect there may some sort of exponential relation. 
  There is need to create multiple independent varible features from one 
  by increasing the power on independent variable each time.At the end 
  multiple columms will be created with one column containing say x,next x^2,x^3...
  This new feature matrix will be used to train the linear regression model 
  to get polynomial regression model.
       In the code at first linear regression and the polynomial linear regression is 
  built to see the difference between the 2  and the accuracy difference between the
  2.
