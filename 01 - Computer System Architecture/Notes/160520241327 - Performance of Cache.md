---
date: 2024-05-16T13:27
tags: []
---
The performance of cache memory is frequently measured in terms of a quantity called ***hit ratio***. 
- When the CPU refers to memory and finds the word in cache, it is said to produce a **hit**.
- If the word is not found in cache, it is in main memory and it counts as a **miss**. 
- The ==ratio of the number of hits divided by the total CPU references to memory== (hits plus misses) is the **hit ratio**.
- The hit ratio is best measured experimentally by running representative programs in the computer and measuring the number of hits and misses during a given interval of time.

 Hit ratios of 0.9 and higher have been reported. This high ratio verifies the validity of the locality of reference property.
- The average memory access time of a computer system can be improved  considerably by use of a cache.
- If the hit ratio is high enough so that most of the time the CPU accesses the cache instead of main memory, the average access time is closer to the access time of the fast cache memory.
- For example, a computer with cache access time of 100 ns, a main memory access time of 1000 ns, and a hit ratio of 0.9 produces an average access time of 200 ns.
- This is a considerable improvement over a similar computer without a cache mem­ory, whose access time is 1000 ns.