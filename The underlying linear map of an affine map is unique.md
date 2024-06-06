---
date: 2023-07-16
tags:
  - mathematics
---
up:: [[Affine Map]]

The underlying linear map $L: V_M \to V_N$ of an affine map $f: A_M \to A_N$ is **unique**. Suppose otherwise: let $L, \tilde{L}: V_M \to V_N$ underlying linear maps for the same $f$. Then
$$
f(A+v) = f(A) + L(v) = f(A) + \tilde{L}(v)
$$
However, since an affine space is defined by a [[Regular Group Action]], any pair of points in it are connected by a unique vector. Thus
$$
\forall v \in V_M, L(v) = \tilde{L}(v) \implies L = \tilde{L}
$$

---
### References
- [Notes on Mathematical Physics for Mathematicians - Daniel Tausk](https://www.ime.usp.br/\~tausk/texts/MathPhysics.pdf)