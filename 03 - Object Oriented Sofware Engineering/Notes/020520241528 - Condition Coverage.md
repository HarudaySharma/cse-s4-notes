---
date: 2024-05-02T15:28
tags: []
---
In this technique, **all individual conditions must be covered** as shown in the following example:

```asm
READ X, Y
IF(X == 0 || Y == 0)
PRINT ‘0’
```
\#**TC1**: X = 0, Y = 55
\#**TC2**: X = 5, Y = 0

