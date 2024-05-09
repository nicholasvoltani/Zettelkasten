---
Date: 2023-07-08
tags:
  - mathematics
---
up:: [[Free Group Action]]

# $(\implies)$
Let there be a [[Free Group Action]] of $G$ over $X$. Let $x \in X$. Then the [[Stabilizer of Group Action|Stabilizer]] of $x$ is 
$$
Stab_x = \{g \in G \mid g \cdot x = x\}
$$

However, by the definition of a free group action, we have that $g \cdot x = x \implies g = e_G$. Thus, $Stab_x = \{e_G\}$.

Thus, the stabilizers of all $x \in X$ are trivial.

# $(\impliedby)$
Let $x \in X$, for which we assume $Stab_x = \{e_G\}$.

Thus, this means that $\forall g \in G, g \cdot x = x \implies g = e_G$, which means that the group action is free.
