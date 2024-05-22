![[Pasted image 20240214110340.png]]

#### [[SR Flip Flop using NAND GATE]]
#### [[SR Flip Flop using NOR GATE]]

***Operations:***

 <u>*Case 1*:</u>
-  $PR=CLR=1$ The asynchronous inputs are inactive and the flip flop responds freely to the $S,R$ and the $CLK$ inputs in the normal way.

 <u>*Case 2*:</u>
-  $PR=0$ and $CLR=1$ This is used when the $Q$ is set to $1$.
 
 <u>*Case 3*</u>
-  $PR=1$ and $CLR=0$ This is used when the $Q’$ is set to $1$.

 <u>*Case 4*</u>
-  $PR=CLR=0$ This is an invalid state.

**Characteristics Equation for SR Flip Flop:**
$Qn+1 = QnR’ + SR’$