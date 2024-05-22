---
date: 2024-05-16T13:26
tags: []
---
The basic operation of the cache is as follows. 

- When the CPU needs to access memory, the cache is examined.
	- If the word is found in the cache, it is read from the fast memory. 
	- If the word addressed by the CPU is not found in the cache, the main memory is accessed to read the word.
- A block of words containing the one just accessed is then transferred from main memory to cache memory. 
- The block size may vary from one word (the one just accessed) to about 16 words adjacent to the one just accessed.
- In this manner, some data are transferred to cache so that future references to memory find the required words in the fast cache memory.
