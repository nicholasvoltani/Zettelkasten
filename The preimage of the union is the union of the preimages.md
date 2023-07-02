---
Date: 2023-07-01
Tags: mathematics
---
up:: [[Preimage of Function]]

Let $f: X \to Y$ be a function and subsets $C, D \subset Y$.

Then let $x \in f^{-1}(C \cup D)$ a point in $f$'s [[Preimage of Function|preimage]]. Then
$$x \in f^{-1}(C \cup D) \iff f(x) \in C \cup D \iff (f(x) \in C) \lor (f(x) \in f(D))$$

By the definition of the preimage of a function, we have that 
$$y \in f^{-1}(C \cup D) \iff (x \in f^{-1}(C)) \lor (x \in f^{-1}(D)) \iff y \in f^{-1}(C) \cup f^{-1}(D)$$

Thus, $f^{-1}(C \cup D) \subseteq f^{-1}(C) \cup f^{-1}(D)$ and $f^{-1}(C \cup D) \supseteq f^{-1}(C) \cup f^{-1}(D)$. 

Therefore, $f^{-1}(C \cup D) = f^{-1}(C) \cup f^{-1}(D)$.
