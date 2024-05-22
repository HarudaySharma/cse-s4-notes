---
date: 2024-05-02T16:17
tags: []
---
>[!example] 
>Given the following values, compute function point when all complexity adjustment factor (CAF) and weighting factors are average.
>User Input = 50
>User Output = 40
>User Inquiries = 35
>User Files = 6
>External Interface = 4 

>[!success] Solution
>**Step-1**: As complexity adjustment factor is average (given in question), hence,
>scale = 3.
>$$F = 14 \times 3 = 42$$
>**Step-2**:
>$$CAF = 0.65 + ( 0.01 \times 42 ) = 1.07$$
>**Step-3**: As weighting factors are also average (given in question) hence we will multiply each individual function point to corresponding values in TABLE.
>$$UFP = (50\times4) + (40\times5) + (35\times4) + (6\times10) + (4\times7) = 628$$
>**Step-4**:
>$$Function\;Point = 628 \times 1.07 = \textcolor{cyan}{671.96}$$
