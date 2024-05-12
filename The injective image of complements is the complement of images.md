---
date: 2023-07-01
tags:
  - mathematics
---
up:: [[The image of the complement contains the complement of the images]] 

Note that, by the definition of an [[Injective Function]], we have that[^1]
$$
\exists x \in X \setminus B \mid f(x) = y \iff (\exists x \in X \mid f(x) = y) \land (\nexists x \in B \mid f(x) = y)
$$
thus proving the reciprocal $f(X) \setminus f(B) \subseteq f(X \setminus B)$.

[^1]: That is due to $\forall y \in Y, {\color{red} \exists!} x \in X \mid f(x) = y$.