---
Date: 2023-07-13
Tags: mathematics
---
up:: [[Affine Space]]

![[Affine Map.excalidraw|300]]

An affine transformation is a map which preserves affine structures ─ i.e. it preserves, in particular, "distances" between points in the set (with respect to the associated group action).

A map between affine spaces $f: (A_M, V_M, +_M) \to (A_N, V_N, +_N)$ is said to be an affine transformation if there is a [[Linear Transformation]] between their respective vector spaces $L: V_M \to V_N$ (which is called the **underlying linear map of $f$**) such that
$$\forall A \in A_M, \forall v \in V_M: f(A + v) = f(A) + L(v)$$
Equivalently, one can say that, for any pair of points $A, B \in V_M$, we have that
$$\overrightarrow{f(A)f(B)} = L\left(\overrightarrow{AB}\right)$$

## Properties
- [[The underlying linear map of an affine map is unique]]
- An affine map which is bijective is an [[Affine Isomorphism]]

---
### References
- [Affine transformation - Wikipedia](https://en.wikipedia.org/wiki/Affine_transformation)
