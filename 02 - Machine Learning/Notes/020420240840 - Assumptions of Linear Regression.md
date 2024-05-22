---
date: 2024-04-02T08:40
tags: []
---
*Below are some important assumptions of Linear Regression.*

>[!note] 
>These are some formal checks while building a Linear Regression model, which ensures to get the best possible result from the given dataset.

##### 1. Linearity:
The ==independent== and ==dependent variables== have a **linear relationship** with one another.

This implies that changes in the dependent variable follow those in the independent variable(s) in a linear fashion. This means that there should be a straight line that can be drawn through the data points. If the relationship is not linear, then linear regression will not be an accurate model.

![[Pasted image 20240402084452.png]]

##### 2. Small or no multicollinearity between the features:

Multicollinearity means high-correlation between the independent variables.
- there should be ==low correlation b/w independent variables==.

Due to multicollinearity, it may difficult to find the true relationship between the predictors and target variables. Or we can say, it is difficult to determine which predictor variable is affecting the target variable and which is not. So, the model assumes either little or no multicollinearity between the features or independent variables.

##### 3. Independence:
- The ==observations in the dataset are independent of each other==.
- This means that the *value of the dependent variable* for **one observation** *does not depend* on the *value of the dependent variable* for **another observation**. 
- If the observations are not independent, then linear regression will not be an accurate model.