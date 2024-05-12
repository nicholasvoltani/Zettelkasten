---
date: 2023-07-27
tags:
  - mathematics
alias: 
---
up:: [[Linear Independence]]

Let $(V, +, \cdot)$ be a [[Vector Space]], and $S \subset V$ a [[Linear Independence|Linearly Independent]] set. 

Let $v \notin [S]$ outside of the [[Spanning Set|Span]] of $S$. Then $S \cup \{v\}$ is linearly independent as well: 
$$
\sum\limits_i \alpha_i v_i + \beta v= 0 \implies \beta = 0
$$
because, if it's not zero, then we'd contradict our hypothesis ($v$ would be inside $S$'s span), since
$$
v = \sum\limits_i \frac{\alpha_i}{\beta} v_i
$$
Thus, since $S$ is linearly independent, we must have that $\alpha_i = 0 \land \beta = 0$.

Thus, $S \cup \{v\}$ is linearly independent.

# Corollaries
- [[A set is linearly dependent iff there is a vector which is a linear combination of previous vectors]], which means constructing a [[Linear Dependence|Linearly Dependent]] set comes from including a vector which is a [[Linear Combination]] of the previous ones
- By contrapositive of the above, it also follows that [[A set is linearly independent iff all its finite subsets are also L.I.]]

---
### References
- [Notas sobre Álgebra Linear](https://nicholasvoltani.github.io/2021-12-27-notas-alglin/)