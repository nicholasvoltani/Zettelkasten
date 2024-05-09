---
Date: 2023-07-01
tags:
  - mathematics
---
up:: [[Image of Function]]

Let $f: X \to Y$ be a function and subsets $A, B \subset X$.

Then let $y \in f(A \cap B)$ a point in $f$'s [[Image of Function|Image]]. Then
$$
y \in f(A \cap B) \iff \exists x \in A \cap B\mid f(x) = y {\color{red}\implies} (\exists x \in A\mid f(x) = y) \; \lor (\exists x \in B\mid f(x) = y)
$$
By the definition of the image of a function, we have that 
$$
y \in f(A \cap B) \implies y \in f(A) \land y\in f(B) \iff y \in f(A) \cap f(B)
$$

Thus, $f(A \cap B) \subseteq f(A) \cap f(B)$. Note that the reciprocal need not necessarily hold, due to the $\color{red} red$ implication holding only one way, generally: there can be more than one point mapping to $y$, coming from $A$ and $B$, and not necessarily from $A \cap B$.

# Counterexample of the equality
![[Pasted image 20230701140008.png|500]]

Let two non-overlapping sets $A, B \subset X$ map to the same point under $f$. Then $A \cap B = \emptyset \implies f(A \cap B) = \emptyset$, and yet $f(A) = f(B) = f(A) = f(A) \cap f(B) \neq \emptyset$. 

Thus, cases in which distinct points can map to the same point break the equality for images of intersections. That is why [[The injective image of intersections is the intersection of images]].

---
### References
- Sutherland, Wilson A. **Introduction to metric and topological spaces**. Oxford University Press, 2009.