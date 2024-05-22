---
date: 2024-04-04T15:21
tags: []
---
- It is sometimes convenient to supplement the ALU circuit in the CPU with a status register where status bit conditions can be stored for further analysis.
- Status bits are also called condition-code bits or flag bits.
- Block diagram of an 8-bit ALU with a 4-bit status register is shown.
- The four status bits are symbolized by C. S, Z, and V. The bits are set or cleared as a result of an operation performed in the ALU.

![[Pasted image 20240404152524.png]]

- Bit C (carry) is set to 1 if the end carry C8 is 1. It is cleared to 0 if the carry is 0.
- Bit S (sign) is set to 1 if the highest-order bit F7, is 1. It is set to 0 if the bit is 0.
- Bit Z (zero) is set to 1 if the output of the ALU contains all O's. !t is cleared to 0 otherwise. In other words, Z = 1 if the output is zero and Z = 0 if the output is not zero.
- Bit V (overflow) is set to 1 if the exclusive-OR of the last two carries is equal to 1, and cleared to 0 otherwise. This is the condition for an overflow when negative numbers are in 2's complement.
- For the 8-bit ALU, V = 1 if the output is greater than + 127 or less than - 128.
- The status bits can be checked after an ALU operation to determine certain relationships that exist between the values of A and B.
- If bit V is set after the addition of two signed numbers, it indicates an overflow condition.
- If Z is set after an exclusive-OR operation, it indicates that A = B