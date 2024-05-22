---
date: 2024-05-02T15:40
tags:
---
cyclomatic complexity defines the **number of independent paths** in the basis set of a program

thus providing you with an upper bound for the number of tests that must be conducted to ensure that all statements have been executed at least once. 

#### Ways to measure Cyclomatic complexity

1. The number of regions of the flow graph corresponds to the cyclomatic complexity. 
2. Cyclomatic complexity V(G) for a flow graph G
$$V(G) = E - N + 2$$
*where*,
E: number of edges in flow graph
N: number of nodes in flow graph
3. Cyclomatic complexity V(G) for a flow graph G is also defined as 
$$V(G) = P + 1$$
*where*,
P: number of predicate nodes in flow graph

#### [[020520241546 - Example of Cyclomatic Complexity|Example of Cyclomatic Complexity]]