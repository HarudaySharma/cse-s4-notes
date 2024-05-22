---
date: 2024-04-27T14:03
tags: []
---
   - The Gaussian kernel, also known as the Radial Basis Fuction (RBF), is commonly used in SVMs.
   - Used to perform transformation when there is no prior knowledge about data.
   - It **measures** the **similarity between two data points** *based on the distance between them*.
   - Parameter `gamma` determines the *influence of a single training example*.
   - Provides flexibility in capturing complex decision boundaries.

   >[!important] Equation: 
 >$$K(x, x') = \exp\left(-\frac{{\|x - x'\|^2}}{{2\sigma^2}}\right)$$