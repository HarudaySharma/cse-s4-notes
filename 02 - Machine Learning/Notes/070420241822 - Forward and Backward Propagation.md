---
date: 2024-04-07T18:22
tags:
---
In ***Forward propagation***,
- the flow of information is from the input layer to the output layer via hidden layer (where the learning happens).
- the network is exposed to the training data and the predicted labels are calculated.
- Now a loss function(error) is calculated comparing the actual and predicted labels 
- and then to minimise this loss function “***Backward propagation***” is performed 
- and a technique named “**Gradient Descent**” is used to reduce this error.

In ***Back Propagation***
- the flow of information is from output layer to the input layer the weights are modified starting from the output layer up to the input layer, so that the predictability of the network increases.

*[[190420241258 - What is Gradient Descent|What is Gradient Descent?]]*