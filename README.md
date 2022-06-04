# AMoDA
Homework and final project for the lecture *Adv. Methods of Data Analysis* by Prof. Neubert, summer term 22 Uni Bonn

## Exercise 1: Maximum-likelihood fitting
Minimisation of a -likelihood function ($\chi^2$) via gradient descent. The gradient descent algorithms are accelerated using batch/stochastic, momentum and Nesterov grad. descent.

**! Due to lots of work during that week the homework is incomplete.**

## Exercise 2: Regression and Classification
### Regression
Fitting polynomials of order 1 to 8 to a gaussian smeared sine function and testing the fit with random new data samples.
### Classification
Implementation of a classifier using the minimization of a 2D-polynomial function.

## Exercise 3: Model selection
Comparing fitted polynomials of order 1 to 8 using different **information criteria** (AIC, BIC, $\chi^2$) and **cross validation**.

## Exercise 4: Multivariate analysis
### Machine Learning for the $\tau^-\to\mu^-\mu^+\mu^-$ search at LHCb
__Aim:__ Train a classifier using $1000$ data points to differentiate _signal_ (target $t=1$) and _background_ ($t=0$). 
* Using the Kolmogorov-Smirnov (KS) test to identify the best features to classify the data.
* Using sklearn to train a Gaussian naive Bayes classifier
* Using sklearn to train a gradient-boosted decision tree
* Calculating and comparing their responses on training and test data
* Checking for overtraining using KS test
* Comparing the performance of the classifiers with their ROC curves


## Final project
t.b.a.