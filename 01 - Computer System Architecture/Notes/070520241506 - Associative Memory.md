---
date: 2024-05-07T15:06
tags: []
---
A ***memory unit accessed by content*** is called an **Associative Memory** or Content Addressable Memory (**CAM**).
- This type of ==memory is Accessed== simultaneously and in Parallel ==on the== ==basis of data content== rather than by specific address of location.
- When a **word is written** in the associative memory, no address is given. The ==memory is capable of finding an empty unused location== to store the word.
- When **word is to be read** from Associative Memory the ==content of the word== or ==Part of the word== is *specified*.
	- The memory locates all words which matches the specified content and marks them for reading.
- because of its organization the associative memory is uniquely ***suited to parallel searches***.
- Searches can be done on an entire word or on a specific field within a word.

---

An associative memory is more expensive than **RAM** because each cell must have storage capability as well as logic circuits for matching the contents with an external argument 
- for this reason associative memory used is in application where the search time is very critical

>[!note] 
>- Jin bits ko search karna => anding with 1
>- Jin bits ko mask karna => anding with 0
#### [[160520241307 - Hardware Organization of Associative Memory|Hardware Organization]]
#### [[160520241317 - Example Associative Memory|Example]]
#### [[160520241315 - Memory Array & External Registers Relationship|Memory Array & External Registers Relationship]]