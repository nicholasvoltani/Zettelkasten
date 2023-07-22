---
Date: 2023-07-13
Tags: mathematics
---
up:: [[Affine Space]]

![[Operations in Affine Space.excalidraw.svg|300]]

Let $(A, V, +)$ be an affine space, and let $O \in A$ be a fixed point (which will play the role of the origin). For all $x \in A$, write $\vec{Ox} = O - x \in V$ as the vector separating $O$ and $x$.

Then the function
$$\begin{align*}
m_O: &A \to V\\
&x \to \vec{Ox}
\end{align*}
$$
is a [[Bijective Function|Bijection]][^1], with inverse 
$$\begin{align*}
m_O^{-1}: &V \to A\\
&v \to O + v
\end{align*}
$$

Using these operators, one can create the [[Vector Space]] operations on $A$ as
$$\begin{align*}
x + y &:= m^{-1}_O(\vec{Ox} + \vec{Oy})\\
\lambda x &:= m^{-1}_O(\lambda \vec{Ox})
\end{align*}
$$

Thus, $A$ can be seen as a vector space, with the fixed point $O$ acting as its origin.

When seeing the affine space as a vector space, [[An affine space with a fixed point is isomorphic to its underlying vector space]][^2], since to each point in $A$ there is only one $v \in V$ ─ thus, being trivially isomorphic to the entire vector space $V$.

---
### References
- [Affine transformation - Wikipedia](https://en.wikipedia.org/wiki/Affine_transformation#Structure)

[^1]: It is [[Surjective Function|Surjective]] due to the space's [[Group Action]] being [[Transitive Group Action|Transitive]], and [[Injective Function|Injective]] due to the action being [[Free Group Action|Free]] ─ i.e. due to the group action being [[Regular Group Action|Regular]].
[^2]: This is true if the entire vector space spans the affine space, which we pressupose due to the group action's domain covering the entirety of $V$, as well as the regularity of the action (that is, there are no "lazy vectors" allowed; all vectors "induce movement" upon the space).