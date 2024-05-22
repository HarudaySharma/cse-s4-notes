Adjusted R squared, as the name suggests, is the **improved version of R squared error**. 
- R square has a limitation of improvement of a score on increasing the terms, even though the model is not improving, and it may mislead the data scientists.
- To overcome the issue of R square, adjusted R squared is used, which will always show a lower value than R².
	- It is because it adjusts the values of increasing predictors and only shows improvement if there is a real improvement.

>[!important] formula
> ![[Pasted image 20240328173427.png]]
> $n => number\;of\;observations$
> $k => number\;of\;independent\;variables$
> $Ra^2 => adjusted\;R^2$ 