---
date: 2024-05-02T12:58
tags: []
---
Calculate approx. cost of development easily in process.

###### Step-1
$$F = 14 \times Scale$$
Scale:

| Weighted Factors |              |
| ---------------- | ------------ |
| 0                | No influence |
| 1                | Incidental   |
| 2                | Moderate     |
| 3                | Average      |
| 4                | Significant  |
| 5                | Essential    |

**0 - 2** => ***Low***
**3** => ***Moderate***
**4 - 5** => ***High***

###### Step-2
Calculate Complexity Adjustment Factor (CAF)
$$CAF = 0.65 + (0.01 \times F)$$

###### Step-3
Calculate underlying point (UFP)

|      Function Point       | Low | Avg | High |
| :-----------------------: | :-: | :-: | :--: |
|   EI (*external inputs*) |  3  |  4  |  6   |
|   EO (*external ouptuts*) |  4  |  5  |  7   |
|  EQ (*external inquires*) |  3  |  4  |  6   |
|   ILF (*internal files*) |  7  | 10  |  15  |
| EIF (*external interfaces*) |  5  |  7  |  10  |

multiply each individual function point to corresponding values in TABLE.

###### Step-4
$$FP = UFP \times CAF$$

#### [[020520241617 - Example of Functional Point|Example]]