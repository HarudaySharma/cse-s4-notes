---
date: 2024-04-04T09:07
tags: []
---
One-address instructions use an implied accumulator (AC) register for all data
manipulation. For multiplication and division there is a need for a second register. However, here we will neglect the second register and assume that the AC contains the result of all operations.

*The program to evaluate* 
$$X = (A + B)  (C + D)$$
*is*
$$\begin{align*}
\text{LOAD } \;\;\;\;\;\;\;\;\;\; A\;\;\;\;\;\;\;\;\;\;\;\;\;  &AC \leftarrow M[A] \\
\text{ADD }  \;\;\;\;\;\;\;\;\;\; B\;\;\;\;\;\;\;\;\;\;\;\;\;&AC \leftarrow AC + M[B] \\
\text{STORE }\;\;\;\;\;\;\;\;\;\; T\;\;\;\;\;\;\;\;\;\;\;\;\;  &M[T] \leftarrow AC \\
\text{LOAD } \;\;\;\;\;\;\;\;\;\; C\;\;\;\;\;\;\;\;\;\;\;\;\;  &AC \leftarrow M[C] \\
\text{ADD }  \;\;\;\;\;\;\;\;\;\; D\;\;\;\;\;\;\;\;\;\;\;\;\;  &AC \leftarrow AC+M[D] \\
\text{MUL }  \;\;\;\;\;\;\;\;\;\; T\;\;\;\;\;\;\;\;\;\;\;\;\;  &AC \leftarrow AC \times M[T] \\
\text{STORE }\;\;\;\;\;\;\;\;\;\; X\;\;\;\;\;\;\;\;\;\;\;\;\;  &M[X] \leftarrow AC
\end{align*}$$
- All operations are done between the AC register and a memory operand. T is the address of a temporary memory location required for storing the intermediate result.