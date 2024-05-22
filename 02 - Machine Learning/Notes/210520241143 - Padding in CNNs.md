---
date: 2024-05-21T11:42
tags: []
---
**Padding** refers to the process of ***adding extra pixels*** (usually zeros) ***around the border*** of an input image ==before it is processed by a convolutional layer==. 

Padding serves several purposes:

1. **Control Output Size:** By adding padding, you can control the spatial dimensions of the output feature maps. Without padding, the output size reduces with each convolution, which can become problematic for deeper networks.
2. **Preserve Information at Borders:** Padding ensures that the convolution operation covers the edges and corners of the image, preserving important features that might otherwise be lost.
3. **Maintain Input Dimensions:** Padding can be used to maintain the same width and height for the input and output feature maps, commonly referred to as "same" padding.

#### [[210520241149 - Types of Padding|Types of Padding]]