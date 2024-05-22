---
date: 2024-04-11T09:26
tags: 
cssclasses:
---
![[Pasted image 20240430164554.png]]

the general structure of 4 segement pipeline is shown:
1. the operands pass through all 4 segments in a fixed sequence
	1. each segment consists of a combinational circuit "S" that performs a sub operation over that data stream flowing through the pipe.
2. the segments are seperated by registors "R" that holds the intermediate results between the stages 
	1. information flows b/w adjacent stages under the control of a common clock applied to all the registers simultaneously 
3. Task:
	1. task is defined as the total operation performed going through all the segments in pipeline.
4. space time diagram illustrates the behaviour of a pipeline and shows the segment utilization as a function of time.
#### [[180420241440 - Space Time Diagram|Space Time Diagram]]
