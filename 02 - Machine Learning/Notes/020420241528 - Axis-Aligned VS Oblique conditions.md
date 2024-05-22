---
date: 2024-04-02T15:28
tags: []
---
An **axis-aligned** **condition** involves only a single feature. An **oblique condition** involves multiple features. For example, the following is an axis-aligned condition:

>[!important] axis-aligned condition
>`num_legs ≥ 2`

>[!important] oblique condition
>`num_legs ≥ num_fingers`

>[!note]
>Often, decision trees are trained with only axis-aligned conditions.
>However, oblique splits are more powerful because they can express more complex patterns.
>- Oblique splits sometime produce better results at the expense of higher training and inference costs.

![[Pasted image 20240402152640.png]]
*Figure 4. Examples of an axis-aligned condition and an oblique condition.*