---
date: 2024-04-03T17:45
tags: []
---
All operations are performed with an implied accumulator register.
- The instruction format in this type of computer uses ==one address field==.

>[!example] For example
>- the instruction that specifies an arithmetic addition is defined by an assembly language instruction as ADD X where X is the address of the operand.
>- The ADD instruction in this case results in the operation
>$$AC \leftarrow AC + M [X]$$
>- AC is the accumulator register and $M [X]$ symbolizes the memory word located at address $X$.

