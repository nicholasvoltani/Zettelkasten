---
Date: 2023-07-08
tags:
  - mathematics
---
up:: [[Transitive Group Action]]

Let $X$ be the base space, and $G$ a [[Group (Mathematics)|Group]]. Let $\alpha: G \times X \to X$ be a [[Transitive Group Action]].

Let $y \in X$. We can know the inverse image of this group action, $\alpha^{-1}(y)$, as follows:
Since it is a transitive action, then $\forall x, y \in X, \exists g_x \in G \mid y = g_x \cdot x$. Acting on the left by $g^{-1}_x$ yields that
$$
g_x^{-1} \cdot y = g^{-1}_x \cdot (g_x \cdot x) = (g^{-1}_x \cdot g_x) \cdot x = x
$$
(the two last equalities follow from identity and compatibility of a group action.)

Thus, a transitive group action is surjective.
