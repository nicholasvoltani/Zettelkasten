---
Date: 2023-07-08
Tags: mathematics
---
up:: [[Stabilizer of Group Action]]

Let there be a [[Group Action]] of $G$ over $X$, and let $x \in X$. Then the stabilizer of $x$ is 
$$
Stab_x = \{g \in G \mid g \cdot x = x\} \subseteq G
$$

## 1. Operation closure
Let $g, h \in Stab_x$. Then 
$$
gh \cdot x = g \cdot (h\cdot x) = g\cdot x = x
$$
which implies that $gh \in Stab_x$

## 2. Identity element
Let $e_G \in Stab_x$, since $e_G \cdot x = x$.

## 3. Inverse element
Let $g \in Stab_x$. Then, since 
$$
x = e_G \cdot x = g^{-1} \cdot g \cdot x = g^{-1} \cdot x
$$
Thus, $g \in Stab_x \implies g^{-1} \in Stab_x$.

Thus, $Stab_x \leq G$ is a [[Normal Subgroup]] of $G$.