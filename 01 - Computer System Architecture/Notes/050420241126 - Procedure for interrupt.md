---
date: 2024-04-05T11:25
tags: []
---
1. The interrupt is usually *initiated by* an ==internal or external signal== rather than from the execution of an instruction.
2. The address of the **interrupt service program (ISR)(ISP)(ISS)** is ==determined by the hardware== rather than from the address field of an instruction.
3. An interrupt procedure ==usually stores all the information necessary to define the state of the CPU== rather than storing only the program counter.

After the ==program has been interrupted== and the *service routine* has been executed the CPU must return to exactly the same state that it was when the interrupt occured.

>[!Note]
>The state of the CPU at the end of the execute cycle (when the interrupt is recognized) is determined from
>1. The content of the Program Counter.
>2. The Content of all Process Registers.
>3. The Content of certain Status Conditions.
