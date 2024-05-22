---
date: 2024-05-13T13:14
tags: []
---
Here the dataset is splitted into “k” number of folds(subsets),where one of these folds is used as testing and the remaining part of the data is used for training the model. Each time a different chunk will be used as test data

![[Pasted image 20240513132223.png]]

>[!note] 
>After each iteration a new instance of a model is created and train-test split is decided according to the new instance

>[!success] Advantage
>Testing is done with diff. Chunks for diff. Data points, with large training data with we will have a much more accurate evaluation

 For eg. if a student is preparing for an exam say for ML and there are approximately 100 PYQs out of which 20 questions are asked to the student and his accuracy is evaluated on his performance on these 20 questions.This method is not a accurate way to calculate his performance and with different questions he can be better tested.

#### [[130520241316 - Applications of K Fold Cross Validation|Applications of K Fold Cross Validation]]
#### [[130520241317 - Advantages of Using K Fold|Advantages of Using K Fold]]
