---
date: 2024-04-02T13:22
tags: []
---

|                            **Ridge Regression**(L2)                            |                                **Lasso Regression**(L1)                                |
| :----------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: |
|                  ==Shrinks== the coefficients ==toward zero==                  |                ==Encourages== some coefficients to be ==exactly zero==                 |
|  Adds a ==penalty term proportional to== the ==sum of squared coefficients==   | Adds a ==penalty term proportional to== the ==sum of absolute values of coefficients== |
|                    Does ==not eliminate== any ==features==                     |                          Can ==eliminate== some ==features==                           |
|             ** ==Not Robust to outliers==, because of square term              |                                 ==Robust to Outliers==                                 |
|              ==Suitable== when ==all features== are ==important==              |          ==Suitable== when ==some features== are irrelevant or ==redundant==           |
|                   ==Requires== setting a ==hyperparameter==                    |                       ==Requires== setting a ==hyperparameter==                        |
| ==Performs better== when there are many ==small to medium-sized coefficients== |              ==Performs better== when there are a ==large coefficients==               |
|               ** ==Used== in ==datasets with complex features==                |                      ==used== in ==dataset with sparse features==                      |

*what are [[150420241452 - Outliers|outliers]]?*