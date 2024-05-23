---
date: 2024-04-18T09:47
tags: []
---
>[!fail] Problem with Programmed I/O
>In the programmed I/O method, the CPU stays in a program loop until the I/O unit indicates that it is ready for data transfer.
>this is a time consuming process since it keeps the processor busy needlessly.

>[!check] Solution
>It can be avoided by using an interrupt facility and special command to inform the interface to issue an interrupt request signal when the data are available from the device.
in the mean time CPU can procced to execute another program.

#### How Interrupt Initiated I/O Works
- the I/O interface keeps on montoring the device and when it determines, device is ready for data transfer.
- It generates interrupt request to the CPU.
- upon detecting the Interrupt request CPU momentarily stops the task it is processing, branches to the service sub-routine to process the I/O transfer and then it returns to the task it was originally performing.