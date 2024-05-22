---
date: 2024-05-15T13:26
tags: []
---
###### Bus Request (BR)
It is the input used by the DMA Controller to **request** the **CPU** to ==relinquish control of buses== (i.e grant the access of buses to DMA Controller).
when this input is active(high)
- the CPU terminates the execution of current instructions and 
- places the address bus, data bus and read/write lines into high impedance state.
- which means output is disconnected and doesn't have a logic significance.
###### Bus Grant (BG)
the CPU activates the BUS Grant output to **inform** the ***DMA*** that the ==buses are in high impedant state==
therefore, ***DMA*** can now ==take control of buses== to conduct **memory transfers without processor intervention**.

---

*when the DMA terminates the transfer* 
- it **disables** the ==bus request line==,
- the the CPU disables the BUS GRANT line
and takes control of buses and return to its normal operation.