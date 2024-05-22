---
date: 2024-05-16T13:15
tags: []
---
![[160520241315 - Memory Array & External Registers Relationship 2024-05-16 13.15.55.excalidraw]]

The relation between the memory array and external registers in an associative memory is shown in Fig.

- The cells in the array are marked by the letter C with two subscripts. 
- The first subscript gives the word number and the second specifies the bit position in the word. 
- Thus cell C9 is the cell for bit j in word i. 
- A bit Ai in the argument register is compared with all the bits in column j of the array provided that Ki = 1. 
- This is done for all columns j = 1, 2, . .., n. 
- If a match occurs between all the unmasked bits of the argu­ment and the bits in word i, the corresponding bit M1 in the match register is set to 1. 
If one or more unmasked bits of the argument and the word do not match, M1 is cleared to 0.  