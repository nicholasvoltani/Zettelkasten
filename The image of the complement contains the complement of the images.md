---
date: 2023-07-01
tags:
  - mathematics
---
up:: [[Image of Function]]

Let $f: X \to Y$ a function, and $B \subseteq X, D \subseteq Y$.

Let $y \in f(X) \setminus f(B)$. Then, by definition of a [[Set Complement]],
$$
(y \in f(X)) \land (y \notin f(B)) \implies (\exists x \in X \mid y = f(x)) \land (\nexists x \in B \mid f(x) = y) {\color{red} \implies} \exists x \in X \setminus B \mid f(x) = y \implies y \in f(X \setminus B)
$$

Thus, $f(X) \setminus f(B) \subseteq f(X\setminus B)$.

Note that the reciprocal does not necessarily hold, $\exists x \in X \setminus B \mid f(x) = y$ doesn't necessarily imply that $\nexists x \in B \mid f(x) = y$ ─ that is, there can still be some point in $B$ that maps to $f(X \setminus B)$.

# Counterexample of the equality
![[Pasted image 20230701143057.png|500]]

Let $X = \{a, b, c\}$, such that $1 = f(a) = f(c) \neq f(b) = 2$. 

Let $C = \{c\}$. Then note that
$$
\begin{cases}
f(C) = \{2\}\\
f(X) = \{1, 2\}\\
f(X \setminus C) = \{1, 2\}
\end{cases}
$$
Thus, $f(X \setminus C) \neq f(X) \setminus f(C)$.

Thus, cases in which distinct points can map to the same point break the equality for images of complements. That is why [[The injective image of complements is the complement of images]].

---
### References
- Sutherland, Wilson A. **Introduction to metric and topological spaces**. Oxford University Press, 2009.