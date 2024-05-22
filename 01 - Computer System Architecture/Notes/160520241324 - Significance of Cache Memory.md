---
date: 2024-05-16T13:23
tags: []
---
If the active portions of the program and data are placed in a fast small memory, the average memory access time can be reduced, thus reducing the total execution time of the program. 

Such a fast small memory is referred to as a **cache memory**.

- It is placed between the CPU and main memory as illustrated in Fig. 

![[160520241324 - Significance of Cache Memory 2024-05-16 13.24.21.excalidraw]]

- The cache memory access time is less than the access time of main memory by a factor of 5 to 10.
- The cache is the fastest component in the memory hierarchy and approaches the speed of CPU components.
- The fundamental idea of cache organization is that by keeping the most frequently accessed instructions and data in the fast cache memory, the average memory access time will approach the access time of the cache.
- Although the cache is only a small fraction of the size of main memory, a large fraction of memory requests will be found in the fast cache memory because of the locality of reference property of programs.
