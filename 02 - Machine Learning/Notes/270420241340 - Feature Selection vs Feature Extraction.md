---
date: 2024-04-27T13:40
tags: []
---
The <u>main difference</u> between feature selection and feature extraction in artificial neural networks (ANNs) lies in <u>how they process and use input data</u>:

|     Aspect     |                                            ***Feature Selection***                                            |                                          ***Feature Extraction***                                           |     |
|:--------------:|:-------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------:| --- |
|   Definition   |                       Selecting a **subset of original features** to use in the model.                        |                        **Transforming original features** into a new representation.                        |     |
|   Objective    |                   **Choose most relevant features**, discard irrelevant or redundant ones.                    |                     **Capture essential information**, reduce dimensionality and noise.                     |     |
|    Methods     |              can be based on *Statistical tests*, *information gain*, *model-based* techniques.               | can be based on *Principal component analysis* (PCA), *linear discriminant analysis* (LDA), *autoencoders*. |     |
| Input to Model |                   Selected subset of original features are directly used as input to model.                   |               Transformed features (latent features) are used directly as an input to model.                |     |
|    Use Case    | applied when dataset contains **Large number of features**, need to **reduce dimensionality** and complexity. |              used where there is **High-dimensional data**, **capturing underlying patterns**.              |     |

>[!summary] In summary 
> - ***feature selection*** focuses on choosing a subset of the original features,
>  while ***feature extraction*** involves transforming the original features into a new representation.
>- Both techniques aim to improve the performance of neural network models by reducing dimensionality, eliminating noise, and capturing relevant information from the input data.