---
date: 2024-04-02T16:09
tags: []
---
- The Information Gain measures the **expected reduction in entropy.** 
- Entropy measures impurity in the data and information gain **measures reduction in impurity in the data**. 
- The *feature* which has *minimum impurity* will be considered as the **root node**.
- Information gain is **used to decide which feature to split** on ==at each step in building the tree==. 
>[!important] forumula
$$Information\; Gain(S, feature) = E(S) - Weighted\;Avg.\;of\;feature$$

>[!example] 
>![[Pasted image 20240402161017.png]]
>Red color has 3 Yes outcome and 3 No outcome whereas yellow has 3 Yes outcome and 1 No outcome.
>- E(S), we have already calculated
>$$E(S) \approx 0.971$$
>$$E(S_{\text Red}) = -\left(\frac{3}{6}\log_2(3) + \frac{3}{6}\log_2(\frac{3}{6})\right) = 1$$
>$$E(S_{\text Yellow}) = -\left(\frac{4}{4}\log_2(4) + \frac{4}{4}\log_2(4)\right) \approx 0.811$$
>$$Weighted Average = \frac{6}{10} \cdot E(S_{\text Red}) + \frac{4}{10} \cdot E(S_{\text Yellow}) = \frac{6}{10} \cdot 1 + \frac{4}{10} \cdot 0.811 = 0.924$$
>$$Information Gain (S, Color) = E(S) - Weighted Average = 0.971 - 0.924 \approx 0.047$$