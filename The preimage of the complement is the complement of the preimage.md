---
date: 2023-07-01
tags:
  - mathematics
---
up:: [[Preimage of Function]]

Let $f: X \to Y$ a function, and $B \subseteq X, D \subseteq Y$.

Let $y \in f(X) \setminus f(B)$. Then, by definition of a [[Set Complement]],
$$
(y \in f(X)) \land (y \notin f(B)) \implies (\exists x \in X \mid y = f(x)) \land (\nexists x \in B \mid f(x) = y) \implies \exists x \in X \setminus B \mid f(x) = y \implies y \in f(X \setminus B)
$$

Thus, $f(X) \setminus f(B) \subseteq f(X\setminus B)$.
