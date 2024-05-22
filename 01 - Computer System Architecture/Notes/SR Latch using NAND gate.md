![[SR-latch-using-NAND-gate.webp]]

|  S  | R   | Qn  | Qn+1 | State     |
| :-: | --- | --- | ---- | --------- |
|  0  | 0   | 0   | X    | Invalid   |
|  0  | 0   | 1   | X    | Invalid   |
|     |     |     |      |           |
|  0  | 1   | 0   | 1    | Reset     |
|  0  | 1   | 1   | 1    | Reset     |
|     |     |     |      |           |
|  1  | 0   | 0   | 0    | Set       |
|  1  | 0   | 1   | 0    | Set       |
|     |     |     |      |           |
|  1  | 1   | 0   | 0    | No change |
|  1  | 1   | 1   | 1    | No Change |