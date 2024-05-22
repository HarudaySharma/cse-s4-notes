---
date: 2024-04-04T08:55
tags: []
---
Computers with three-address instruction formats can use each address field to specify either a processor register or a memory operand. The program in assembly language that evaluates 
$$X = (A + B)\times(C + D)$$
is shown below, together with comments that explain the register transfer operation of each instruction.
$$ADD \;\;\; R1,\:A,\: B \;\;\;\;\;\;\;  R1 \leftarrow M[A]+M[B]$$
$$ADD \;\;\; R2,\: C,\: D \;\;\;\;\;\;\;  R2 \leftarrow M[C]+M[D]$$
$$MUL \;\;\; X,\:R1,\:R2 \;\;\;\;\;\;\;\;\;  M[X] \leftarrow R1 \times R2$$
- It is assumed that the computer has ==two processor registers==, **R1** and **R2**. The symbol $M [A]$ denotes the ==operand at memory address symbolized by== **A**. 
- The advantage of the three-address format is that it results in short programs when evaluating arithmetic expressions. The disadvantage is that the binary-coded instructions require too many bits to specify three addresses.

>[!example] An Example
>of a commercial computer that uses three-address instructions is the Cyber 170.
> The instruction formats in the Cyber computer are restricted to either three register address fields or two register address fields and one memory address field.