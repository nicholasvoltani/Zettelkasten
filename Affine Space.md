---
Date: 2023-07-11
Tags: mathematics
---
up:: [[021a MOC Linear Algebra]]

> "An affine space is like a vector space that has forgotten its origin." (John Baez)

![[Pasted image 20230711214305.png|300]]

An affine space consists of a triple $(A, V, +)$, where $A$ is a set, $V$ is a [[Vector Space]] (over $\mathbb{K}$) and $+: A \times V \to A$ is a [[Group Action]] which is [[Regular Group Action|Regular]] (i.e. [[Free Group Action|free]] and [[Transitive Group Action|transitive]]) of the additive group $(V, +)$ of its underlying vector space $V$.

Transformations which preserve affine structures are called [[Affine Map]]s.

# Properties
## Vectors act as translations of points in the space
Vectors $\vec{ab} \in V$ act as "parallel displacements": for each point $a \in A$, one can go to $b \in A$ via group action[^2], as
$$
b = a + \vec{ab}
$$
There needs to be at least one such $\vec{ab}$ for each $a, b \in X$ due to transitivity, and there is only one such $\vec{ab}$ since the group action is free. 

## Affine spaces are $\mathbb{K}$-torsors
Therefore, one can see the "**difference between points**" in the affine space as being vectors in $V$. In fact, an affine space is an example of a $V$-[[Torsor]] (seeing $V$ as the additive group $(V, +)$).

## Fixing a point induces a vector space
Picking a fixed point $O \in X$, one can prove that [[Fixing a point in an affine space induces a vector space]] via the bijection $m_O: A \leftrightarrow V$. Through this function (and its inverse $m_O^{-1}$), one can induce vector space operations on $X$ as
$$
\begin{align*}
x + y &:= m^{-1}_O(\vec{Ox} + \vec{Oy})\\
\lambda x &:= m^{-1}_O(\lambda \vec{Ox})
\end{align*}
$$

A consequence of this is that [[An affine space with a fixed point is isomorphic to its underlying vector space]].

---
### References
- [torsors (John Baez)](https://math.ucr.edu/home/baez/torsors.html)
- ARNOL'D, Vladimir Igorevich. **Mathematical methods of classical mechanics**. Springer Science & Business Media, 2013.
- [Notes on Mathematical Physics for Mathematicians - Daniel Tausk](https://www.ime.usp.br/\~tausk/texts/MathPhysics.pdf)
- [Affine spaces | Mauricio Poppe](https://www.mauriciopoppe.com/notes/mathematics/geometry/affine-spaces/)

[^2]: Existence of this vector between any two points in $A^n$ is guaranteed by the transitive property, and being free guarantees it to be unique.