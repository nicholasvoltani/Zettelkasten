---
Date: 2023-07-01
tags:
  - mathematics
---
up:: [[Preimage of Function]]

Let $f: X \to Y$ be a function and subsets $C, D \subset Y$.

Then let $x \in f^{-1}(C \cap D)$ a point in $f$'s [[Preimage of Function|preimage]]. Then
$$
x \in f^{-1}(C \cap D) \iff f(x) \in C \cap D \iff (f(x) \in C) \land (f(x) \in f(D))
$$

By the definition of the preimage of a function, we have that 
$$
y \in f^{-1}(C \cap D) \iff (x \in f^{-1}(C)) \land (x \in f^{-1}(D)) \iff y \in f^{-1}(C) \cap f^{-1}(D)
$$

Thus, $f^{-1}(C \cap D) \subseteq f^{-1}(C) \cap f^{-1}(D)$ and $f^{-1}(C \cap D) \supseteq f^{-1}(C) \cap f^{-1}(D)$. 

Therefore, $f^{-1}(C \cap D) = f^{-1}(C) \cap f^{-1}(D)$.
