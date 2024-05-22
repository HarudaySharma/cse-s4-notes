Also called **Toggle Flip Flop**
![[Pasted image 20240214140634.png]]
 
![[Pasted image 20240214174949.jpg]]

| Clock |  T  | Qn  | Qn+1 |       State        |
|:-----:|:---:|:---:|:----:|:------------------:|
|  ⬆️   |  0  |  0  |  0   |     No change      |
|   ⬆   |  0  |  1  |  1   |     No change      |
|       |     |     |      |                    |
|   ⬆   |  1  |  0  |  1   |       Toggle       |
|       |     |     |      | **Race Condition** |
|   ⬆   |  1  |  1  |  0   |       Toggle       |
|       |     |     |      |                    |
|  🔽   |  X  |  0  |  0   |     No Change      |
|  🔽   |  X  |  1  |  1   |     No Change      |

**Characteristic Equation**
$Qn+1 = TQn' + T'Qn$
==XOR Condition==