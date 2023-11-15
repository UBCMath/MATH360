# Logistic Regression

## Bid Ideas

Let $(x_1,y_1),\dots,(x_N,y_N)$ be a dataset such that the target values are binary: $y_k = 0$ or $1$ for all $k=1,\dots,N$. The goal of logistic regression is to construct a **logistic function** $\sigma(x;W,b)$ which best fits the data by minimizing a cost function such as **cross entropy**. The logistic regression model $\sigma(x;W,b)$ takes values in the interval $(0,1)$ and we use the function to **classify** new data $x$ by assigning the target $y=0$ if $\sigma(x,W,b) < 1/2$ and $y = 1$ if $\sigma(x;W,b) > 1/2$. The hyperplane $\sigma(x;W,b) = 1/2$ defines the **decision boundary**.

## Learning Goals

* Summarize properties of the logistic function and the weight and bias parameters
* Compare and contrast cost functions for logistic regression models such as mean least squares and cross entropy
* Implement regularization terms in cost functions and tune regularization parameters
* Approximate optimal model parameters for logistic regression models using `sklearn`