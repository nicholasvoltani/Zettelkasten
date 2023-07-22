---
Date: 2023-07-08
Tags: mathematics
alias: Group actions partition a set into its orbits
---
up:: [[Orbit of Group Action]]

Let there be a [[Group Action]] of $G$ over $X$, and let $x \in X$. 

Define the [[Equivalence Relation]] over $X$ as
$$x \sim y \iff \exists g \in G: y = g \cdot x$$
Note that it is an equivalence relation, since
- $x \sim y$ via $g \in G$ $\iff$ $y \sim x$ via $g^{-1} \in G$
- $x \sim y$ via $g$, and $y \sim z$ via $h$ $\implies$ $x \sim z$ via $gh$
- $x \sim x$ via $e_G$

Note that the [[Quotient Space]] is the set of [[Orbit of Group Action|Orbit]]s[^1], since
$$Orb_x = \{y \in X \mid \exists g \in G: y = g \cdot x\} = [x]$$

Thus, we have that a group action partitions a set into its orbits (under this action).

[^1]: I.e. orbits $\iff$ equivalence classes.