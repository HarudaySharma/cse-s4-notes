---
date: 2024-05-02T13:07
tags: []
---
given by Halstead's Law of analytics

>[!note] terminologies
>n1 = no. of distinct Operators in a program
>n2 = no. of distinct operands in a program
>N1 = total no. of Operators
>N2 = total no. of Operands 

these all can be used to find program length, program volume, program difficulty, effort and so on...

$$Program \; Length\:(N) = N1 + N2$$
$$Program \; Vocabulary\:(n) = n1 + n2$$
$$Volume\:(V) = N \times (\log_2 n)$$

>[!example] 
>```c
>if(k < 2) {
>	if(k > 3)
>		x = x * k;
>}
>```
>Distinct Operators (n1): `if () {} >< = *;`
>Distinct Operands (n2): `K 2 3 X`
>- n1 = 10, n2 = 4, N1 = 13, N2 = 7
>$$Length = \textcolor{cyan}{N} = N1 + N2 = 13 + 7 = \textcolor{cyan}{20}$$
>$$Vocabulary = \textcolor{orange}{n} = n1 + n2 = 10 + 4 = \textcolor{orange}{14}$$
>$$Volume = \textcolor{yellow}{V} = 20 \log_2(14) = 20 \times 3.807354 = \textcolor{yellow}{76.147}$$
