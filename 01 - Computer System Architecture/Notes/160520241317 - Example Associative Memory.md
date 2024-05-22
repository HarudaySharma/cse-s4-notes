---
date: 2024-05-16T13:17
tags: []
---
>[!example]
>- suppose that the argument register A and the key register K have the bit configuration shown below. Only the three leftmost bits of A are compared with memory words because K has 1's in these positions. 
> `A        101  111100`
> `K        111  000000`
> `Word-1   100  111100    No Match` 
> `Word-2   101  000001   Match` 
>- Word 2 matches the unmasked argument field because the three leftmost bits of the argument and the word are equal.