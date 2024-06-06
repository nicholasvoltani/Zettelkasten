---
date: 2023-07-16
tags:
  - mathematics
---
up:: [[Affine Isomorphism]]

![[Affine Map.excalidraw|300]]

Let $(E, V, +_E)$ and $(E', V', +_{E'})$ be [[Affine Space]]s[^1]. Let $f: E \to E'$ be an [[Affine Isomorphism]] with underlying linear map $L: V \to V'$.

# Affine map is bijective $\implies$ Underlying map is isomorphism
Let $f: E \to E'$ be an affine isomorphism ([[Affine Map]] which is a [[Bijective Function|Bijection]]). Then, for any $A \in E, v \in V$, we have
$$
f(A+v) = f(A) + L(v)
$$
Since $f$ has an inverse, we have that
$$A+v = f^{-1}(f(A)+ L(v))$$
Since the inverse is also an affine map, we have that
$$
A+v = A + \tilde{L}(L(v))
$$
where $\tilde{L}: V' \to V$ is the underlying linear map associated to $f^{-1}$.

However, note that, since an affine space is determined by a [[Regular Group Action]], then there is one and only one vector connecting $A$ and $A+v$, which is $v$. Thus,
$$
\forall v \in V, \tilde{L}(L(v)) = v \implies \tilde{L} = L
$$
And, thus, the underlying linear map of an affine isomorphism is a [[Vector Space Isomorphism]].

# Affine map is not bijective $\implies$ Underlying map is not an isomorphism
Let $f: E \to E'$ not be an affine isomorphism; then it is not [[Injective Function|Injective]] or it's not [[Surjective Function|Surjective]] (or neither).

Suppose $f$ is not injective. Then there are $A \neq B \in E \mid f(A) = f(B)$, in which case $\overrightarrow{AB} \neq0$ but $\overrightarrow{f(A)f(B)} = 0$. Thus, $L$ is not an isomorphism, since it does not take an origin to an origin (i.e. it's not injective).

Suppose $f$ is not surjective. Then there are points in $E'$ which are not reached by $f$. 
Let $P \in E' \setminus f(E)$. Then there are points in $E'$ which have a distance of, say, $w \in V'$ from $P$ and which are still in $E'$. ==?????==




---
### References
- [Notes on Mathematical Physics for Mathematicians - Daniel Tausk](https://www.ime.usp.br/\~tausk/texts/MathPhysics.pdf)

[^1]: $V'$ is just a vector space (possibly) unrelated to $V$. Not to be confused with $V$'s dual.