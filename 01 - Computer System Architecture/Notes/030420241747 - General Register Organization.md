---
date: 2024-04-03T17:45
tags: []
---
The instruction format in this type of computer needs three register address fields.

Thus the instruction for an arithmetic addition may be written in an assembly language as
- **ADD** $R1$ , $R2$ , $R3$ to denote the operation 
$$R 1 \leftarrow R2 + R3$$
- The number of address fields in the instruction can be reduced from three to two if the destination register is the same as one of the source registers.
- Thus the instruction **ADD** $R1$ , $R2$ would denote the operation .
$$R 1 \leftarrow R 1 + R2$$
- Only register addresses for $R1$ and $R2$ need be specified in this instruction.
- Computers with multiple processor registers use the move instruction with a mnemonic **MOV** to symbolize a transfer instruction.
- Thus the instruction **MOV** $R1$ , $R2$ denotes the transfer 
$$R1 \leftarrow R2$$
*OR*
$$R2 \leftarrow R1$$
*depending on the particular computer.*
- Thus transfer-type instructions need two address fields to specify the source and the destination.
- General register-type computers ==employ two or three address fields in their instruction format==. Each address field may specify a processor register or a memory word.
- An instruction symbolized by **ADD** $R1$ , $X$ would specify the operation.
$$R1 \leftarrow R1 + M[X]$$
- It has two address fields, one for register $R1$ and the other for the memory address $X$.
