---
date: 2024-04-02T09:04
tags: []
---
- Lasso Regression also known as “**L1**” **regularization**, is a method for stopping overfitting in linear regression models by including a penalty term in the cost function.
- Penalty equivalent to the **absolute value of the magnitude of coefficients**
$$Minimization\;objective(Cost\;function) = RMSE + \alpha \times (sum\;of\;the\;absolute\;value\;of\;coefficients)$$
- Cost function which allows Lasso regression to eliminate least important features i.e. it performs auto feature selection.

1. **α(alpha) = 0:**
	- The objective becomes the same as simple linear regression.

*Figure 4:
Comparing coefficient magnitudes for lasso regression with different values of alpha and ridge regression*
![[Pasted image 20240402090637.png]]

In Figure 4 for alpha=1, we not only see that most of the coefficients are zero , but that the remaining coefficients are also small in magnitude. Decreasing alpha to 0.01, we obtain the solution shown as the green dots, which causes most features to be exactly zero. Using alpha=0.00001, we get a model that is quite unregularized, with most coefficients nonzero and of large magnitude. 
