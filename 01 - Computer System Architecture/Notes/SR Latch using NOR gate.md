![[Pasted image 20240214170917.png]]

| $S$ | $R$ |  $Q(n + 1)$   |
|:---:|:---:|:-------------:|
|  0  |  0  | **NO CHANGE** |
|  0  |  1  |     **0**     |
|  1  |  0  |     **1**     |
|  1  |  1  |  **INVALID**  |

---

|  S  | R   | Qn  | Qn+1 | State     |
| :-: | --- | --- | ---- | --------- |
|  0  | 0   | 0   | 0    | No change |
|  0  | 0   | 1   | 1    | No change |
|     |     |     |      |           |
|  0  | 1   | 0   | 0    | Reset     |
|  0  | 1   | 1   | 0    | Reset     |
|     |     |     |      |           |
|  1  | 0   | 0   | 1    | Set       |
|  1  | 0   | 1   | 1    | Set       |
|     |     |     |      |           |
|  1  | 1   | 0   | X    | INVALID   |
|  1  | 1   | 1   | X    | INVALID   |