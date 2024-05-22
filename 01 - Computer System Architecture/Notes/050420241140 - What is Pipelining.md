---
date: 2024-04-05T11:40
tags: []
---
Pipelining is a technique of **breaking sequential process into small fragments** or sub operations. 

The ==execution== of each of these sub operations ==takes place in a certain dedicated segment== that **operates concurrently** (together) with **all other segements**.


- A pipeline can be visualised as a collection of processing segments through which binary information flows,
	- ==Each segement performs partial processing== dictated by the way the task is partitioned.
- The ==result obtained== from the computation in ==each segment is transferred to the next segement== in the pipeline.
- The **final result** is obtained ==after the data have passed through all segments==.
##### How is it possible?
- The overlapping of computation is ==made possible by associating a register with each segment in the pipeline== 
- The register provider isolation between each segement so that each can operate on distinct data simultaneously.

>[!note] 
>*Numerical will be there* 

