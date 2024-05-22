---
date: 2024-04-18T14:31
tags: []
---
>[!example] 
> $A_i \times B_i + C_i$
> `for (i = 1....7)`
>- each sub operation is to be implemented in a segment within a pipeline
>  *drawing here*
>- each segment has one or two registers and a combinational circuit
>
>| Clock pulse no. | Segment 1 | Segment 2  |  Segment 3   |
>|:---------------:|:---------:|:----------:|:------------:|
>|                 | **R1 R2** | **R3 R4**  |    **R5**    |
>|        1        |   A1 A2   |   __ __    |      __      |
>|        2        |   A2 B2   | A1 * B1 C1 |      __      |
>|        3        |   A3 B3   | A2 * B2 C2 | A1 * B1 + C1 |
>|        4        |   A4 B4   | A3 * B3 C3 | A2 * B2 + C2 |
>|        5        |   A5 B5   | A4 * B4 C4 | A3 * B3 + C3 |
>|        6        |   A6 B6   | A5 * B5 C5 | A4 * B4 + C4 |
>|        7        |   A7 B7   | A6 * B6 C6 | A5 * B5 + C5 |
>|        8        |   __ __   | A7 * B7 C7 | A6 * B6 + C6 |
>|        9        |   __ __   |   __ __    | A7 * B7 + C7 |

>[!note] 
>- any operation that can be decomposed into a sequence of sub operations of about the same complexity can be implemented by a pipeline processor
>- the technique is efficient for those operations that need to repeat the same tasks many time with different sets of data.

