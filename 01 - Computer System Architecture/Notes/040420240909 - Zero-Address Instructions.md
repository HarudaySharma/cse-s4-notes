---
date: 2024-04-04T09:08
tags: []
---
A stack-organized computer does not use an address field for the instructions ADD and MUL. The PUSH and POP instructions, however, need an address field to specify the operand that communicates with the stack.

*The following program shows how* 
$$X = (A + B) \times (C + D)$$

*will be written for a stackorganized computer*. 

>[!Note]
> (TOS stands for top of stack.)

$$\begin{align*}
\text{PUSH  }\;\;\;\;\;\;\;\;\;\;\; A \;\;\;\;\;\;\;\;\;\;\;\;&TOS\leftarrow A \\
\text{PUSH  }\;\;\;\;\;\;\;\;\;\;\; B \;\;\;\;\;\;\;\;\;\;\;\; &TOS\leftarrow B \\
\text{ADD}\;\;\;\;\;\;\;\;\;\;\;  \;\;\;\;\;\;\;\;\;\;\;\; &TOS\leftarrow (A+B) \\
\text{PUSH } \;\;\;\;\;\;\;\;\;\;\;C\;\;\;\;\;\;\;\;\;\;\;\;  &TOS\leftarrow C  \\
\text{PUSH  }\;\;\;\;\;\;\;\;\;\;\; D \;\;\;\;\;\;\;\;\;\;\;\; &TOS\leftarrow D \\
\text{ADD   }\;\;\;\;\;\;\;\;\;\;\; \;\;\;\;\;\;\;\;\;\;\;\; &TOS\leftarrow (C+ D) \\
\text{MUL  } \;\;\;\;\;\;\;\;\;\;\; \;\;\;\;\;\;\;\;\;\;\;\;  &TOS \leftarrow  (C+D)\times (A+B) \\
\text{POP  } \;\;\;\;\;\;\;\;\;\;\;X\;\;\;\;\;\;\;\;\;\;\;\;  &M[X]\leftarrow TOS
\end{align*}
$$

- To evaluate arithmetic expressions in a stack computer, it is necessary to convert the expression into reverse Polish notation. The name "zero-address" is given to this type of computer because of the absence of an address field in the computational instructions.