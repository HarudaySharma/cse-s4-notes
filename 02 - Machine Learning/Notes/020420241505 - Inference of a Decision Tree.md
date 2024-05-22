---
date: 2024-04-02T15:05
tags:
  - Decision-Tree-Use-Case
---
Inference of a decision tree model is computed by routing an example from the root, to one of the leaf nodes according to the conditions. The value of the reached leaf is the decision tree's prediction. The *set of visited nodes is called* the **inference path**. 

>[!example] 
>consider the following feature values:
>
>The prediction would be _dog_. The inference path would be:
>1. num_legs ≥ 3 → Yes
>2. num_eyes ≥ 3 → No
>
>![[Pasted image 20240402150514.png]]
>*Figure 2. The inference path that culminates in the leaf dog on the example {num_legs : 4, num_eyes : 2}*

