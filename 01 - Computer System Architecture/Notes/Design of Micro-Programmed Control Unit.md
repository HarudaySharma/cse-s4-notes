---
cssclasses:
  - embed-white
---
###### *design of micro-programmed control unit*
![[Pasted image 20240330164211.png]]	

>[!note] explanation
>- Micro-programming is a collection of micro-instruction. Each micro-instruction mainly contains 3 micro-operation phases. They are F1, F2, F3. In addition to these 3 fields, we have condition field, branch field and address field. 
>- Decoding F1, F2 and F3 fields, the size of all 3 fields are 3 bits each, so a 3X8 decoder decodes this. From the F1 micro-operation phase, we get 8 outputs. Out of these 8 outputs, one output remains unused. 
>- Likewise, the F2 operation also gives a total of 7 outputs, as in the case of F1.
>- In the F3 micro-operation phase, we can perform only 6 operations(one remains unused, and the other is stored for future purposes).
>- So here, in total, we can perform 20 micro-operations (7+7+6). 
>- The diagram above out of 20 operations demonstrates 5 micro-operations. 
>- Output 3 of F2 is connected to ALU. It performs AND operation on the content of the accumulator(AR) and data register(DR) and transfers the result to the accumulator. It is represented as: AC←AC AND DR
>	- And we apply clock pulse on the corresponding accumulator. Load input is enabled to load it on the accumulator.
>- Output 1 of F1 performs ADD operation by ALU on data register and accumulator and transfers the result to the accumulator.
>- Output 5 of F1 performs DRTAR operation, i.e. transfer the contents of data register to the address register. But the size of the data register is 16 bits, whereas the size of the address register is only 12 bits, so the rightmost significant 12 bits of the data register are transferred to the address register.
>- Output 6 of F1 performs PCTAR operation, i.e. transfer the contents of the program counter to the address register.