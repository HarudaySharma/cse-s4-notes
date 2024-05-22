---
date: 2024-05-16T13:07
tags: []
---
*hardware organization*
![[160520241307 - Hardware Organization of Associative Memory 2024-05-16 13.08.53.excalidraw]]

The block diagram of an associative memory is shown in Fig. 
- It consists of a memory array and logic for m words with n bits per word. 
- The argument register A and key register K each have n bits, one for each bit of a word. 
- The match register M has m bits, one for each memory word. 
- Each word in memory is compared in parallel with the content of the argument register. 
- The words that match the bits of the argument register set a corresponding bit in the match register. 
- After the matching process, those bits in the match register that have been set indicate the fact that their corresponding words have been matched. 
- Reading is accomplished by a sequential access to memory for those words whose corresponding bits in the match register have been set. 
- The key register provides a mask for choosing a particular field or key in the argument word. 
- The entire argument is compared with each memory word if the key register contains all 1's. 
- Otherwise, only those bits in the argument that have 1's in their corresponding position of the key register are compared. 
- Thus the key provides a mask or identifying piece of information which specifies how the reference to memory is made. 