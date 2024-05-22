---
date: 2024-05-15T13:24
tags: []
---
###### 1. Address register
- it contains an address to specify the desired location in memory.
- the address register is incremented after each word is transferred to memory.
###### 2. Word Count register
- it specifys the number of words that must be transferred.
- this register is decremented by 1, after each word transfer and the value is internally tested for 0.
###### 3. Control register
- It specifys the mode of transfer.

----

the CPU initialises the DMA by sending the following through the data bus.
1. the starting address of the memory block for read or write.
2. the word count i.e. the number of words in memory block.
3. control to specify the mode of transfer such as read or write.