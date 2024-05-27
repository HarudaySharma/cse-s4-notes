---
cssclasses: [embed-white, ]
---

Also called ***Transparent Latch OR Transparent Flip Flop***

![[Pasted image 20240214140351.png]]

![[d-flip-flop.webp]]

| Clock |  D  | Qn  | Qn+1 |       State        |
| :---: | :-: | :-: | :--: | :----------------: |
|  ⬆️   |  0  |  0  |  0   | **  NO CHANGE   ** |
|   ⬆   |  0  |  1  |  0   |   **  RESET   **   |
|       |     |     |      |                    |
|   ⬆   |  1  |  0  |  1   |  **    SET     **  |
|   ⬆   |  1  |  1  |  1   |  **    SET     **  |

**Characteristic Equation** :
$Qn+1 = D$