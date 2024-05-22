---
date: 2024-04-11T14:20
tags: []
---
>[!tldr] sub operations for floating point addition using arithemtic pipeline
>1. Compare the exponent
>2. Align the mantises
>3. Add or Sub mantises
>4. Normalize the result

>[!example] floating point addition using arithmetic pipeline
>$$a = m \times e$$
>$$m: \; mantisa$$
>$$e: \; exponent$$
>*e.g.*
>$$x = 0.9504 \times 10^3$$
>$$y = 0.8200 \times 10^2$$
>$$z = x + y$$
>1. Make exponent same
>$$x = 0.9504 \times 10^3$$
>$$y = 0.08200 \times 10^3$$
>2. calculate z
>$$z = 1.0324 \times 10^3$$

