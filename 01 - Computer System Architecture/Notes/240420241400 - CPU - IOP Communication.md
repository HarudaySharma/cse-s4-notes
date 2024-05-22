---
date: 2024-04-24T14:00
tags: 
cssclasses:
  - center-images
---
*10 MARKS*
![[Pasted image 20240424140135.png]]
The communication b/w CPU & IOP is shown in the block diagram,

In most cases, memory unit acts as a message center where each processor leaves information for the other.
 the sequence of operations that are carried in the flow chart are as follows:-
1. The CPU sends an instruction to **test the IOP Path**
2. The IOP responds by **inserting a STATUS WORD** in memory for the CPU to check.
	- The bits the status word indicate the condition of the IOP and I/O device such as 
		- IOP overload condition,
		- device busy with another transfer or device ready for another I/O transfer.
3. The CPU refers to the STATUS WORD in memory to decide what to do next.
	- If all is in order, the CPU sends an instruction to start I/O transfer.
	- the memory address recieved with this instruction tells the IOP where to find its program.
4. The CPU can now continue with another program while the IOP is busy with the I/O program.
	- Both programs refer to memory by means of DMA transfer.
5. When the IOP terminates the execution of its program sends an Interrupt request to the CPU.
6. The CPU responds to the IOP by issuing an instruction to read the STATUS from IOP
7. The IOP responds by placing the content of its STATUS report into a specified memory location.
	- The STATUS word indicates whether the transfer has been completed or if any errors occured during the transfer.
8. From inspection of bits in the STATUS WORD CPU determines if the I/O operation was completed satisfactory without errors.


akjbcjksdbsdjkvbsdkv
jkcbkacbsakcbaskcas
aqdborevnvdvds

jkabkjverpvnqwkn