# Overview

## Big Ideas

Suupose a variable $y$ depends on be independent variables $x_1,\dots,x_p$. Use the notation $\mathbf{x} = (x_1,\dots,x_p) \in \mathbb{R}^p$ to denote the vector of independent variables.  The construction of a **data-driven model** consists of the following steps:

A **data-driven model** is a function $f(x,\beta)$ and relates an independent variable $x$ to an dependent variable $

$$
y = f(x;\beta) + \varepsilon
$$

which depends on a parameter $\beta$
where $\varepsilon$ is the error.

When the dependent variable is continuous then we call 


* Observe samples $y_0,\dots,y_N$ of the dependent variable and corresponding values $\mathbf{x}_0,\dots,\mathbf{x}_N$ of the dependent variables 
* Choose a regression function $f(\mathbf{x}; \boldsymbol{\beta})$ which depends on some vector of parameters $\boldsymbol{\beta} = (\beta_0,\beta_1,\dots)$
* Choose a cost function $C$ which measures the goodness-of-fit of the function $f$ relative to the observed data
* Compute the parameters $\boldsymbol{\beta}$ which minimize the cost $C$
* Analyze the regression model $y = f(\mathbf{x} ; \boldsymbol{\beta}) + \varepsilon$ where $\varepsilon$ is the random error representing the discrepancy in the approximation

## Learning Goals

*Under construction*