---
date: 2024-04-04T14:03
tags: []
---
The addressing mode specifies a rule for interpreting or modifying the address
field of the instruction code before the ==operand== is actually referenced.

1. **Implied mode** => operand is in the Accumulator.
2. **Immediate mode** => the operand part of the instruction code is the data itself.
3. **Register mode** => the operand part contains the register number of the register in whose data is to be operated.
4. **Register indirect mode** => the operand part contains the register number of the register in which the effective address of the data is stored.
5. **Autoincrement or autodecrement mode** => register content is incremented or decremented.
6. **Direct address mode** => the operand contains the effective address of the data.
7. **Indirect address mode** => the operand part contains the address of a memory location which contains the effective address of the data.
8. **Relative address mode** => offset is provided which is to be used with the program counter to get the address of the data.
