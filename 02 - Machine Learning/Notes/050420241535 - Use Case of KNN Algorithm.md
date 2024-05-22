---
date: 2024-04-05T15:35
tags: []
---
Let’s take a simple case to understand this algorithm. Following is a spread of red circles (RC) and green squares (GS):

![[Pasted image 20240405153613.png]]

You intend to find out the class of the blue star (BS). BS can either be RC or GS and nothing else. The “K” in KNN algorithm is the nearest neighbor we wish to take the vote from. Let’s say K = 3. Hence, we will now make a circle with BS as the center just as big as to enclose only three data points on the plane. 

![[Pasted image 20240405153637.png]]

The three closest points to BS are all RC. Hence, with a good confidence level, we can say that the BS should belong to the class RC. Here, the choice became obvious as all three votes from the closest neighbor went to RC. The choice of the parameter K is very crucial in this algorithm. 
