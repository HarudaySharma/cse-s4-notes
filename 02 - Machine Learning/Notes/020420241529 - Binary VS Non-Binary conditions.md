---
date: 2024-04-02T15:29
tags: []
---
Conditions with two possible outcomes (for example, true or false) are called **binary conditions**. Decision trees containing only binary conditions are called **binary decision trees**.

**Non-binary conditions** have more than two possible outcomes. Therefore, non-binary conditions have more discriminative power than binary conditions. Decisions containing one or more non-binary conditions are called **non-binary decision trees**.

![[Pasted image 20240402152956.png]]
*Figure 6: Binary versus non-binary decision trees.*

>[!note] 
>A non-binary condition can be emulated with multiple binary conditions; therefore, binary trees are not inherently less powerful than non-binary trees.

---
The most common type of binary condition is the **threshold condition** expressed as:
`feature ≥ threshold`

>[!example] 
>`num_legs ≥ 2`

Other types of conditions exist. Following are other commonly used types of binary conditions:

*Table 2. Common types of binary conditions.*
![[Pasted image 20240402153431.png]]