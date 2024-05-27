---
date: 2024-04-18T09:56
tags: 
---
In DMA the **I/O interface has direct access to memory bus**. Thus, transfers data into and out of the memory through the memory bus.
- the CPU initiates the transfer, 
	- by supplying the interface with the ==starting address== 
	- and the ==number of words== needed to be transferred 
	- and then proceed to execute other tasks.
- when the transfer is made, 
	- the DMA request memory cycles through the memory bus.
	- when the request is granted to the DMA Controller it tranfers the data directly into the memory.

![[180420240956 - Direct Memory Access (DMA) 2024-04-18 10.08.30.excalidraw]]
#### [[180420241001 - DMA in detail|DMA in Detail]]