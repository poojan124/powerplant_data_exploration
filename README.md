# This is about powerplant data exploration and regression.

##### Data can be found here : https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant

In this project i used different regression models to predict hourly electrical energy output(EP).You will find full description about in this file [a relative link](data_description.txt). 
#
Linear regression(using sklearn) leads to mse ~ 21 test and ~20 train.    
#
Feed Forward neural network(using keras) with simple linear activation function and 2 hidden layers.After finding optimal parameters it gives mse ~21 test and ~21 train.Comparing to linear regression its almost same preformace.

