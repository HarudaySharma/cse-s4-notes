---
date: 2024-04-05T11:43
tags: 
---
*diagram missing*
- Multiple functional units help execution of parallel processing, in the block diagram the ==execution unit is seperated into== 8 ==functional units== operating in parallel 
- The Operands in the registers are applied to on of the unit depending on the operation specified by the instruction associated with the operands  c
- The operation performed in each functional unit is indicated in each block of the diagram
- The *Adder* and *Integer* **Multiplier** perform the arithmetic operations, with integer numbers.
- The floating point operations are seperated into 3 circuits operating in parallel 
- The logic, shift and increment ==operations can be performed concurrently on different data.==
- ==All units are independent of each other==, so one number can be shifted while another number is being incremented.
- A multi functional organization is ==associated with a complex control unit== to ==coordinate all the activities among the various components==.