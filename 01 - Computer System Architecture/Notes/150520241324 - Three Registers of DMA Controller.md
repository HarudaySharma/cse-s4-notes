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
- It specifys the mode of transfer (Read/Write).