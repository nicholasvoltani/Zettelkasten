---
Date: 2023-07-08
tags:
  - mathematics
alias: Transitive
---
up:: [[Group Action]]

![[Pasted image 20230708000521.png|300]]

A [[Group Action]] is said to be transitive if, for any two points in the base space $X$, there exists some element in the group which "connects" them.

That is, given a base space $X$ and a [[Group (Mathematics)|Group]] $G$ which acts upon $X$ (e.g. on the left), 
$$
\forall x, y \in X, \exists g \in G \mid y = g\cdot x
$$

# Corollary
[[Transitive Group Actions are Surjective]], since for all points $y \in X$, $\exists (g_x, x = g_x^{-1} \cdot y) \in (G, X)$ such that $g_x \cdot x = y$.

---
### References
- [Group action - Wikipedia](https://en.wikipedia.org/wiki/Group_action)