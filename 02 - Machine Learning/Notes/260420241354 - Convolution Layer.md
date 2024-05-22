---
date: 2024-04-26T13:54
tags: []
---
##### **Aim**:
As while classifying images there are a lot of missing pixels, so we use filters to match them in the corresponding nearby locations and get overall better at finding *similarity* than directly trying to match the entire image
##### **Steps involved in convolution layer**
1. The filter and the image are lined up
2. Then we multiply the image with the corresponding filter
3. Add these values and find their sum
4. Divide the sum by the total number of pixels to find a value which is then placed at the centre(can be moved) of the *filtered image*
5. Repeat these steps for each and every filter

*several filters are used*