---
date: 2024-05-02T15:30
tags: []
---
In this technique, **all** the **possible combinations of the possible outcomes of conditions are tested** at least once.

Let’s consider the following example:

```
READ X, Y
IF(X == 0 || Y == 0)
PRINT ‘0’
```
\#**TC1**: X = 0, Y = 0
\#**TC2**: X = 0, Y = 5
\#**TC3**: X = 55, Y = 0
\#**TC4**: X = 55, Y = 5