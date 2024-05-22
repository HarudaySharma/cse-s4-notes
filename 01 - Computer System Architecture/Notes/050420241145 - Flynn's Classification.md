---
date: 2024-04-05T11:45
tags: []
---
It is one of the way of achieving parallel processing proposed by *MJ Flynn*.
- There are variety of ways that parallel processing can be classified.
	- It can be considered from, the internal organization of the processors, from the interconnection structure b/w processors or from the flow of information through the system. 
- *MJ Flynn* classification considers the ==organization of a computer system by the number of instructions== and ==data items that are manipulated simultaneously==.

##### How is it classified ?
The normal operation of a computer is to fetch instructions from memory, and execute them in the processor.
- The sequence of instructions read from memory constitutes the **instruction stream**.
- The operations performed on the data in the processor constitutes a **data stream**.

==Parallel processing may occur in the instruction stream, in the data stream or in both.==

 *So flynn's classification divide the computers into **4** major groups*
 
### Classification of Computers
#### 1. [[050420241147 - Single instruction stream single data stream (SISD)|Single instruction stream single data stream (SISD)]]
#### 2. [[050420241148 - Single instruction stream multiple data stream (SIMD)|Single instruction stream multiple data stream (SIMD)]]
#### 3. [[050420241149 - Multiple instruction stream single data stream (MISD)|Multiple instruction stream single data stream  (MISD)]]
#### 4. [[050420241150 - Multiple instruction stream multiple data stream (MIMD)|Multiple instruction stream multiple data stream (MIMD)]]