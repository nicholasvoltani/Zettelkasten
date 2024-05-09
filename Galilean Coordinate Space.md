---
Date: 2023-07-20
Tags: physics
---
up:: [[Galilean Space]]

A galilean coordinate space is the [[Canonical Affine Structure of  a Vector Space]] $\mathbb{R} \times \mathbb{R}^3$ from $(\mathbb{R}^4, +, \cdot)$, where we consider $(\mathbb{R}^3, \left<\cdot, \cdot\right>)$ an [[Euclidean Vector Space]]. 

Note that this space is trivially a [[Galilean Space]], since
1. [[Every vector space induces an affine space]][^1] 
2. One can define a time functional as merely the distance in the first $\mathbb{R}$ axis[^2]. Formally, 
$$
\begin{align*}
t: (\mathbb{R} \times \mathbb{R}^3, +) &\to \mathbb{R}\\
(\Delta t, \Delta \vec{x}) &\mapsto \Delta t
\end{align*}
$$
3. The distance between simultaneous events can be created from the [[Vector Space Norm]] induced by the [[Inner Product]] from the [[Euclidean Structure]]

# Possible transformations of this space
- [[Galilean boosts preserve the Galilean Structure]]

## Translations preserve galilean structure
Since [[Translations in affine spaces are affine automorphisms]], every translation $T(t, \vec{x}) = (t+\tau, \vec{x} + \vec{v})$.

## Rotations of the coordinate axes preserve galilean structure
Rotation of the coordinate axes: $\tilde{R}(t, \vec{x}) = (t, R\vec{x})$, where $R \in O(3)$ is an [[Orthogonal Transformation]]



---
### References
- ARNOL'D, Vladimir Igorevich. **Mathematical methods of classical mechanics**. Springer Science & Business Media, 2013.
- [Notes on Mathematical Physics for Mathematicians - Daniel Tausk](https://www.ime.usp.br/\~tausk/texts/MathPhysics.pdf)

[^1]: Since [[Fixing a point in an affine space induces a vector space]].
[^2]: Thinking about $(\mathbb{R} \times \mathbb{R}^3, +, \cdot)$ as the underlying vector space to the set $\mathbb{R} \times \mathbb{R}^3$.