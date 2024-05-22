---
date: 2024-04-04T14:56
tags: 
---
- ==Instructions== are always ==stored== in ==successive memory locations==.
- ==When processed== in the CPU, the ==instructions== are ==fetched from consecutive memory locations== and executed.
- ==Each time== an instruction is ==fetched from memory==, the ==program counter is incremented== so that it contains the address of the next instruction in sequence.
- ==After== the execution of a ==data transfer== or ==data manipulation instruction==, ==control returns to the fetch cycle== with the program counter containing the address of the instruction next in sequence.
- ==On the other hand==, a ==program control type of instruction==, ==when executed==, ==may change the address value in the program counter== and cause the ==flow of control to be altered==.

>[!tldr] 
> In other words, program control instructions specify conditions for altering the content of the program counter, while data transfer and manipulation instructions specify conditions for data-processing operations.

- The change in value of the program counter as a result of the execution of a program control instruction causes a break in the sequence of instruction execution. 
- This is an important feature in digital computers, as it provides control over the flow of program execution and a capability for branching to different program segments.
- ==Branch and jump instructions may be conditional or unconditional==. An unconditional branch. When executed, the branch instruction causes a transfer of the value of ADR into the program counter.
- A conditional skip instruction will skip the next instruction if the condition is met.
- The call and return instructions are used in conjunction with subroutines.
- The compare instruction performs a subtraction between two operands, but the result of the operation is not retained.
- Similarly, the test instruction performs the logical AND of two operands and updates certain status bits without retaining the result or changing the operands.

|           Name           | Mnemonic |                                    Description                                     |
|:------------------------:|:--------:|:----------------------------------------------------------------------------------:|
|          Branch          |    BR    |     Jump to a different location in the program if a certain condition is met      |
|           Jump           |   JMP    |            Jump to a different location in the program unconditionally             |
|           Skip           |   SKP    |              Skip the next instruction if a certain condition is met               |
|           Call           |   CALL   |                   Call a subroutine and store the return address                   |
|          Return          |   RET    |                              Return from a subroutine                              |
| Compare (by subtraction) |   CMP    |  Compare two values by subtracting them and setting the status flags accordingly   |
|     Test (by ANDing)     |   TST    | Perform a bitwise AND operation on two values and set the status flags accordingly |
