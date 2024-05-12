---
date: 2023-07-08
tags:
  - mathematics
---
up:: [[Normal Subgroup]]

Let $G$ be a [[Group (Mathematics)|Group]] and $N \trianglelefteq G$ a [[Normal Subgroup]]. 

Let $g \in G$. We seek to prove that $gN = Ng$. It follows trivially from "summing zeros".

## 1) $gN \subseteq Ng$
Let $gn \in gN$. Then
$$
gn = gn(g^{-1} g= \underbrace{(g n g^{-1})}_{\in N} g \in Ng
$$
by the definition of normal subgroup.

## 2) $Ng \subseteq gN$
Let $ng \in Ng$. Then, similarly,
$$
ng = (g g^{-1}) ng= g\underbrace{(g^{-1} n g)}_{\in N} \in gN
$$
by the definition of normal subgroup.

Thus, $gN = Ng$ for normal subgroups.