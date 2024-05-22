---
date: 2024-04-02T08:55
tags: []
---
- Regularization’ technique penalizing the magnitude of coefficients of features and minimizing the error between predicted and actual observations.
- Performs **L2 regularization**, i.e., adds penalty equivalent to the **square of magnitude of the coefficients**.
- The penalty term regulates the magnitude of the coefficients in the model and is proportional to the sum of squared coefficients.

$$Minimization\;objective(Cost\;function) = RMSE + \alpha \times (sum\;of\;square\;of\;coefficients)$$

1. α(alpha) = 0:
	- The objective becomes the same as simple linear regression. We’ll get the same coefficients as simple linear regression.

*Figure 3. Comparing coefficient magnitudes for ridge regression with different values of alpha and linear regression.*
![[Pasted image 20240402090233.png]]

Here, the x-axis enumerates the entries of coef_: x=0 shows the coefficient associated with the first feature, x=1 the coefficient associated with the second feature, and so on up to x=100. The y-axis shows the numeric values of the corresponding values of the coefficients. The main takeaway here is that for alpha=10, the coefficients are mostly between around –3 and 3. The coefficients for the Ridge model with alpha=1 are somewhat larger. The dots corresponding to alpha=0.1 have larger magnitude still, and many of the dots corresponding to linear regression without any regularization (which would be alpha=0) are so large they are outside of the chart.
