---
date: 2024-04-01T16:46
tags: 
cssclasses:
  - embed-white
---
>[!question] 
>While there are different accuracy parameters, then why do we need a Cost function for the Machine learning model ?

>[!example] 
>Suppose we have a dataset that contains the height and weights of cats & dogs, and we need to classify them accordingly. If we plot the records using these two features, we will get a scatter plot as below:
>
>![[Pasted image 20240401164715.png]]
>
>In the above image, the green dots are cats, and the yellow dots are dogs. Below are the three possible solutions for this classification problem.
Cost Function in Machine Learning
>
>![[Pasted image 20240401165258.png]]
>
>In the above solutions, all three classifiers have high accuracy, but the third solution is the best because it correctly classifies each datapoint. The reason behind the best classification is that it is in mid between both the classes, not close or not far to any of them.
>To get such results, we need a Cost function. It means for getting the optimal solution; we need a Cost function. It calculated the difference between the actual values and predicted values and measured how wrong was our model in the prediction. By minimizing the value of the cost function, we can get the optimal solution.
