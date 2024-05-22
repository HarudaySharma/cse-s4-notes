---
date: 2024-05-02T15:46
tags: []
---
>[!example] 
>```
>i = 0;
>n=4;
>
>while (i<n-1) do
>j = i + 1;
>
>while (j<n) do
>
>if A[i] < A[j] then
>
>swap(A[i], A[j]);
>end do;
>j=j+1;
>
>end do;
>```
>*Flow graph for this program will be*
>![[Pasted image 20240502155218.png]]
>V(G) = 4 *(number of non-overlapping regions)*
>V(G) = 9 – 7 + 2 = 4 *(E - N + 2)*
>V(G) = 3 + 1 = 4 (Condition nodes are 1,2 and 3 nodes) *(Predicate Nodes)*

>[!important] Independent Paths
>- 1, 7
>- 1, 2, 6, 1, 7
>- 1, 2, 3, 4, 5, 2, 6, 1, 7
>- 1, 2, 3, 5, 2, 6, 1, 7
