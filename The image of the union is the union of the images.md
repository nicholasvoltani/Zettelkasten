---
date: 2023-07-01
tags:
  - mathematics
---
up:: [[Image of Function]]

Let $f: X \to Y$ be a function and subsets $A, B \subset X$.

Then let $y \in f(A \cup B)$ a point in $f$'s [[Image of Function|Image]]. Then
$$
y \in f(A \cup B) \iff \exists x \in A \cup B\mid f(x) = y \iff (\exists x \in A\mid f(x) = y) \; \lor (\exists x \in B\mid f(x) = y)
$$

By the definition of the image of a function, we have that 
$$
y \in f(A \cup B) \iff y \in f(A) \lor y\in f(B) \iff y \in f(A) \cup f(B)
$$

Thus, $f(A \cup B) \subseteq f(A) \cup f(B)$ and $f(A \cup B) \supseteq f(A) \cup f(B)$. 

Therefore, $f(A \cup B) = f(A) \cup f(B)$.
