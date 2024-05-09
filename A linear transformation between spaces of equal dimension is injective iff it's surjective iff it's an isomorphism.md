---
Date: 2023-07-28
tags:
  - mathematics
alias: 
---
up:: [[Linear Transformation]]

Let $T: U \to V$ a linear transformation between [[Vector Space]] **with equal [[Finitely Generated Vector Space Dimension|Dimension]]** $\dim U = \dim V = n$.

We seek to prove that 
- **A)** Bijectiveness $\iff$ 
- **B)** Injectiveness $\iff$ 
- **C)** Surjectiveness

It is trivial that $A) \implies B)$ and that $A) \implies C)$.

# Injective $\implies$ Bijective
By the [[Kernel-Image Theorem]], we have that 
$$
\dim U (= \dim V) = \dim Im T
$$
Thus, the dimension of the codomain is equal to the dimension of $T$'s image ─ which implies that $T$ is [[Surjective Function|Surjective]], and thus [[Bijective Function|Bijective]].

# Surjective $\implies$ Bijective
If $T$ is surjective, we have that $\dim V = \dim Im T$, for which we have that
$$
\dim \ker T = 0
$$
for which $T$ is [[Injective Function|Injective]], since [[A linear transformation is injective iff its kernel is trivial]].

## Corollaries
- [[An endomorphism is injective iff it's surjective]]

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho & Mary Lilian Lourenço. Editora EDUSP.