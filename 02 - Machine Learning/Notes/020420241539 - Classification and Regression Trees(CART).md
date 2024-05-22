---
date: 2024-04-02T15:39
tags: []
---
Tree analogy is generally represented by **CART** known as **Classification And Regression Tree**.

- CART is simple to understand, interpret, visualize and requires little effort for data preparation. Moreover, it performs feature selection.
- While growing a tree below points are to be considered :
	- Features to choose
	- Conditions for splitting
	- To know where to stop
	- Pruning

The decision to make a strategic split heavily affects the accuracy of the tree and the ==decision criteria for regression and classification trees will be different==.

- **Entropy/Information gain** or **Gini Index** can be used for choosing the best split.
	- Entropy and Information gain go hand in hand.
- For a given dataset with different features, to decide *which feature* to be **considered as the root node** and which *feature* should be the **next decision node** and so on,
	- **information gain of each feature** should be known.

>[!note] 
>The *feature which has maximum information gain will be considered as the root node*. 
- To calculate information gain first we should calculate the entropy.

#### terminologies in CART
##### [[020420241543 - Entropy|Entropy]]
##### [[020420241609 - Information Gain|Information Gain]]
##### [[020420241621 - Gini Index|Gini Index]]
##### [[020420241627 - Pruning|Pruning]]

---
#### [[230420241633 - Entropy & Info Gain Numericals|Entropy & Info Gain Numericals]]
