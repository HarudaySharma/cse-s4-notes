---
date: 2024-04-03T17:46
tags: []
---
- Computers with stack organization would have PUSH and POP instructions which require an address field.
- Thus the instruction PUSH X will push the word at address X to the top of the stack.
- The stack pointer is updated automatically.
- **Operation-type instructions do not need an address field in stack-organized computers**. This is because the operation is performed on the two items that are on top of the stack. 
- The instruction ADD in a stack computer consists of an operation code only with no address field.
- This operation has the effect of popping the two top numbers from the stack, adding the numbers, and pushing the sum into the stack. There is no need to specify operands with an address field since all operands are implied to be in the stack.