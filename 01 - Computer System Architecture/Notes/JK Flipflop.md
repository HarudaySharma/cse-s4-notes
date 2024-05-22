*Developed to overcome shortcoming of **[[SR Flip Flop]]**.*
![[Pasted image 20240214111248.png]]
![[JK-Flip-Flop-800x444.webp]] 

| **$J$** | **$K$** | **$Q$** | **$Q(n + 1)$** | **STATE** |
|:-----:|:-----:|:-----:|:------:| --------- |
|   0   |   0   |   0   |   0    | **NO CHANGE** |
|   0   |   0   |   1   |   1    | **NO CHANGE** |
|   0   |   1   |   0   |   0    | **RESET** |
|   0   |   1   |   1   |   0    | **RESET** |
|   1   |   0   |   0   |   1    | **SET** |
|   1   |   0   |   1   |   1    | **SET** |
|   1   |   1   |   0   |   1    | ***SET*** |
|   1   |   1   |   1   |   0    | ***RESET*** |


***Operations:***

 <u>*Case 1:*</u>
-  $PR=CLR=0$ This condition is in its invalid state.
 
 <u>*Case 2:*</u>
-  $PR=0$ and $CLR=1$ The $PR$ is activated which means the output in the $Q$ is set to $1$. Therefore, the flip flop is in the set state.
 
 <u>*Case 3:*</u>
-  $PR=1$ and $CLR=0$ The $CLR$ is activated which means the output in the $Q’$ is set to $1$. Therefore, the flip flop is in the reset state.
 
 <u>*Case 4:*</u>
-  $PR=CLR=1$ In this condition the flip flop works in its normal way whereas the $PR$ and $CLR$ gets deactivated.

**Characteristics Equation for SR Flip Flop:**
$Qn+1 = QnK’ + JQn’$

#### [[Race Around Condition JK Flip Flop]]