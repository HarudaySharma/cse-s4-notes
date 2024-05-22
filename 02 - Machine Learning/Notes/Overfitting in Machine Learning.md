*Overfitting refers* 
to a **model that models the training data too well**.
- Overfitting *happens* when a ==model learns the <u>detail</u> and <u>noise</u> in the training data== to the ==extent that it <u>negatively impacts</u> the performance== of the model **on new data**.
	- This means that the ==noise== or ==random fluctuations== in the training data is ==picked up and learned as concepts by the model==.
	- The problem is that ==these concepts do not apply to new data== and ==negatively impact the models ability to generalize==.
- Overfitting is more likely with **nonparametric** and **nonlinear models** that have more ==flexibility when learning a target function==.
	- As such, many nonparametric machine learning algorithms also include parameters or techniques to limit and constrain how much detail the model learns.

>[!example]
>- *decision trees* are a nonparametric machine learning algorithm that is very flexible and is subject to overfitting training data.
>	- This problem can be addressed by pruning a tree after it has learned in order to remove some of the detail it has picked up.

>[!summary] 
> **Overfitting**:
>- Good performance on the training data, poor generliazation to other data.