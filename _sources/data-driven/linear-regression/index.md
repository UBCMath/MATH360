# Linear Regression

A **linear regression model** is of the form

$$
y = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + \dots + \beta_p x_p + \varepsilon
$$

where:

* $y$ is the dependent variable (called the **target**)
* $x_1,\dots,x_p$ are the independent variables (called the **features**)
* $\varepsilon$ is the **residual**

The construction of a linear regression model usually consists of the following steps:

* Observe samples $(\mathbf{x}_1,y_1),\dots,(\mathbf{x}_N,y_N)$ (where each $\mathbf{x}_i = (x_{i,1},\dots,x_{i,p})$ is a vector of the independent variables)
* Choose a cost function $C$ such as the **residual sum of squares**
* Compute the parameters $\beta_0,\beta_1,\dots,\beta_p$ which minimize the cost $C$