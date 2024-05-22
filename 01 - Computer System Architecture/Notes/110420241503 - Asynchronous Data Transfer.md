---
date: 2024-04-11T15:03
tags: []
---
1. the ==internal operations== in a digital system are ==synchronized by means of== **clock pulses** supplied by a ==common pulse generator== 
2. Clock pulses are applied to all registers within a unit and all data transfer among internal registers occur simultaneously during the occurence of a clock pulse.
3. ==Two units== such as a **CPU** and an **I/O interface** are ==designed independently== of each other. 
	- **if** the ==registers in the interface share a common clock with the CPU regsiters== the transfer b/w the two units is said to be **synchronous**
4. <u>In most cases</u> the ==internal timing in each unit is independent from the other== in that case ==each unit uses it's own clock== for internal registers.
5. In that case the units are said to be **Asynchronous** to each other.
6. **Asynchronous data transfer** b/w two independent units *<u>require that control signals be transmitted b/w the communicating units</u>* to ==dedicate the time at which data is being transmitted==.

*following are the methods for this.*
#### [[110420241506 - Methods for Async Data Transfer|Methods for Asynchronous Data Transfer]]

*Asynchronous Communication Interface*
![[110420241506 - Async Communication Interface 2024-04-17 14.12.05.excalidraw]]