---
date: 2024-04-03T17:02
tags: 
cssclasses:
  - embed-white
  - center-images
---
Suppose we have a dataset that has two classes (green and blue). We want to classify that the new data point as either blue or green.

![[Pasted image 20240403170438.png]]

To classify these points, we can have many decision boundaries, but the question is which is the best and how do we find it?

>[!note] 
> Since we are plotting the data points in a 2-dimensional graph we call this decision boundary a straight line but if we have more dimensions, we call this decision boundary a “hyperplane”

![[Pasted image 20240403170746.png]]

A hyper-plane is a plane in space that is used to separate the two data points classes. The ==main task of the SVM model is to find the best hyper-plane to classify data points==.

The best hyperplane is that plane that has the maximum distance from both the classes, and this is the main aim of SVM. This is done by finding different hyperplanes which classify the labels in the best way then it will choose the one which is farthest from the data points or the one which has a maximum margin.

![[Pasted image 20240403170929.png]]

