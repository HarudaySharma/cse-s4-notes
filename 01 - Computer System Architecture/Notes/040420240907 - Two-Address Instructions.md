---
date: 2024-04-04T09:07
tags: []
---
Two-address instructions are the most common in commercial computers. Here again each address field can specify either a processor register or a memory word.

*The program to evaluate*
$$X = (A + B) \times (C + D)$$
*is as follows:*

$$\begin{align*}
\text{MOV } \;\;\;\;\;\;\;\;\;\;\;\; R1,\: A\;\;\;\;\;\;\;  &R1 \leftarrow M[A] \\
\text{ADD } \;\;\;\;\;\;\;\;\;\;\;\; R1,\: B \;\;\;\;\;\;\; &R1 \leftarrow R1 + M[B] \\
\text{MOV } \;\;\;\;\;\;\;\;\;\;\;\; R2,\: C\;\;\;\;\;\;\;  &R2 \leftarrow M[C]  \\
\text{ADD } \;\;\;\;\;\;\;\;\;\;\;\; R2,\: D\;\;\;\;\;\;\; &R2 \leftarrow R2 + M[D] \\
\text{MUL } \;\;\;\;\;\;\;\;\;\;\;\; R1,\:R2  \;\;\;\;\;\;\; &R1 \leftarrow R1 \times R2 \\
\text{MOV } \;\;\;\;\;\;\;\;\;\;\;\; X, \:R1\;\;\;\;\;\;\;  &M[X] \leftarrow R1 
\end{align*}$$
- The MOV instruction moves or transfers the operands to and from memory and processor registers. The first symbol listed in an instruction is assumed to be both a source and the destination where the result of the operation is transferred.