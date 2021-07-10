# Logistic_Regression

a model that yields a binary dependent variable. Mathematically, a binary logistic model has a dependent variable with two possible values, such as pass/fail which is represented by an indicator variable, where the two values are labeled "0" and "1".

### let's derive for the binary cross-entropy for logistic regression:





### Let's build a logistic regression classifier to recognize cats :)


we will use gradient descent as an optimization algorithm

1. First, we process the images. Get them ready to feed into the model

2. Second, We use logistic regression in a neural network 


Functions we have to process:
1. Sigmoid function: for classification purposes
2. Initialize matrix(weight and bias)

<br>

propagate function(forward and backward):

forward-propagation, followed by backward prop, for learning the parameters

We get input features X

Using X to compute for the logit A = sigma(wTX + b)

Calculate the cost function

<br>

optimization function(gradient descent):
Learn the weights and bias term by minimizing the cost function, this is done using theta = theta - alpha\*dtheta

<br>

Lastly, a function to combine everything:
