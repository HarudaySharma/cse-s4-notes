---
date: 2024-04-03T17:10
tags: 
cssclasses:
  - embed-white
---
![[030420241710 - Mathematical Intution behind SVM 2024-05-21 16.01.23.excalidraw]]
*The hyper-plane can be expressed by the following equation.*

>[!important] projection formula
>$$y = \omega^T x + b$$
>- $\omega$ is a vector of constants that represent the slopes of the plane.


>[!example] 
>In this example, the vector can be represented with two constants **-1** and **0**.
>Now, let’s take two data points, one from each class, and find the projection of them to the hyper-plane.
>Assuming that the hyper-plane is passing through origin so, b = 0.
>
>- For the first data point ( 4,  4), after substituting it to the hyper-plane equation, we find that the value of y is negative.
>$$y=\begin{bmatrix}-1\\ 0\end{bmatrix}\begin{bmatrix}4&4\end{bmatrix}$$
>$$y = -1 * 4 + 0* 4 = -4 \rightarrow \text negative$$
>
>- For the second data point ( -4, -4), the value of y will be positive.
>$$y=\begin{bmatrix}-1\\ 0\end{bmatrix}\begin{bmatrix}-4&-4\end{bmatrix}$$
>$$y = -1 * -4 + 0* -4 = 4 \rightarrow positive$$
>
>We see that the projection of any data point at one side of the hyper-plane is always positive and at the other side is always negative
>
>- Now, we need to find the equation of the hyper-plane and the margin at the two sides of the hyper-plane in order to classify the data points.
> 
> To find the margin lines, we will assume that the margin lines are passing through the nearest points in each class. so, the equations of the margin lines (or planes) are as follows.
>$$\omega^T x + b = 0 \;\;\;\;\; \text{the equation of hyper-plane}$$
>$$\omega^T x_1 + b = -1 \;\;\;\;\; \text{the equation of the margin line in the positive area}$$
>$$\omega^T x_2 + b = 1 \;\;\;\;\; \text{the equation of the margin line in the negative area}$$
>- To find the distance between two margin lines, we subtract the two data points, and hence, we find the following equation.
>$$\omega^T (x_2 - x_1) = 2 \;\;\;\;\;$$
>$$x_2 - x_1 = \frac{2}{||\omega^T||} \;\;\;\;\;$$
>From the equation shown above, we need to maximize this function in order to find the best margin planes which guarantee that no data points are misclassified (this means that the minimum number of data points should be located in the margin areas and no data points are located in the other class).
