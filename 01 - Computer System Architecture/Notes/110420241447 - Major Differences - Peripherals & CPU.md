---
date: 2024-04-11T14:47
tags: []
---
1. peripheral are electro mechanical and electromagnetic devices and CPU and Memory are *electronic devices*.
	- So there manner of operation is different from the operation of the CPU.
		- Therefore, a **conversion of signal values** may be required.
2. the **data transfer rate** of peripherals is usually slower than the transfer rate of the CPU and therefore,
	- a **synchronization mechanism** may be required.
3. **data codes** and formats in peripherals *differ* from the **word format** in the CPU and Memory.
4. the **operating modes** of peripherals are *different* from *each other* and 
	- each must be **controlled** so as *not to disturb* the *operation of other peripherals connected* to the CPU.

>[!success] Resolution
>To resolve these differences Computer Systems include special hardware components b/w the CPU and peripherals to supervise and synchronize all input and output transfers.
>these components are called **IO Interface Units** because they interface b/w the processor bus and peripheral device.
>e.g. 
>- 8279(interface unit) -> keyboard interface
>- 8255 -> PPI
>- DMA (direct memory access)


