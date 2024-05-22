---
date: 2024-05-13T13:36
tags: []
---
>[!question] Why is random initialisation of weights essential?

>[!success] solution
>Random initialization of weights is an essential step in training neural networks. It is the process of assigning initial weights to the neurons of the network before training. The initial weights are usually chosen randomly from a specified distribution, and their values can significantly impact the network's performance.
>
>The goal of random initialization is to ensure that each neuron in the network starts with a different initial weight. If all the neurons start with the same initial weight, then they will learn the same features, and the network will not be able to learn complex patterns. Moreover, random initialization helps in preventing the neurons from getting stuck in a local minima during training.

>[!question] Having the same bias is prefered or not?

>[!success] solution
>Having the same bias for all neurons in a hidden layer is not generally advisable, as it limits the flexibility and capacity of the neural network to learn complex patterns and relationships within the data.
>
>The bias term in a neural network allows each neuron to have an offset or a baseline activation level, which is crucial for the network's ability to learn and model nonlinear relationships in the data. If all neurons in a hidden layer share the same bias, it means they all start from the same initial activation level, which can constrain the model's ability to capture diverse features and patterns in the input data.
>
>Neural networks are powerful because they can learn to represent complex functions by adjusting both the weights and biases of the connections between neurons. By having different biases for each neuron, the network can learn to capture different aspects of the input data, leading to richer representations and better performance.
>
>Additionally, allowing different biases for each neuron helps prevent symmetry in the network, which can lead to overfitting and poor generalisation. Symmetry occurs when multiple neurons in a layer have the same weights and biases, causing them to behave identically during training and limiting the network's ability to learn distinct features.
>
>In summary, giving each neuron in a hidden layer its own bias term allows the neural network to learn more flexible and expressive representations of the data, leading to better performance and generalisation.