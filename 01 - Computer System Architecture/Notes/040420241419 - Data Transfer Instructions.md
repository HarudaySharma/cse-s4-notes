---
date: 2024-04-04T14:19
tags: 
cssclasses: []
---
Data transfer instructions **move data** from
One place in the computer to another *without changing the data content*.
- Most of the ==data tranfer== is ==b/w memory and processor registers==,
- ==B/w processor registers and input or output== and 
- ==B/w the processor register themselves==.

| ***Name*** | ***Mnemonic*** |
|:----------:|:--------------:|
|    Load    |       LD       |
|   Store    |       ST       |
|    Move    |      MOV       |
|  Exchange  |      XCH       |
|   Input    |       IN       |
|   Output   |      OUT       |
|    Push    |      PUSH      |
|    Pop     |      POP       |

1. Load: 
	- The load instuction is used to designate a transfer from memory to a processor register usually an Accumulator
2. Store:
	- The store instuction is designated a transfer from processor register into memory.
3. Move:
	- The move instuction is used b.w  multiple CPU register to designate a tranfer from one register to another
	- Also used for transfer b.w CPU registers and Memory or b.w two memory words.
4. Exchange:
	- exchange instruction is used to swap instruction b/w two registers, or a register and memory word.
5. IN OUT
	- The input and output instruction transfer data among processor registors and input and output terminals.
6. PUSH / POP
	 - the push and pop instructions tranfer data between processor registers and a memory stack.
 
 *ON push => SP content is decremented*