---
Date: 2023-07-16
tags:
  - mathematics
---
up:: [[021a MOC Linear Algebra]]

A vector space over a [[Field (Algebra)]] $\mathbb{K}$ is a triple $(V, +, \cdot)$, where $V$ is a (non-empty) set, with operations $+$ and $\cdot$ under which
1. $(V, +)$ is an [[Abelian Group]]
	- The sum is commutative, associative, has identity $0$ and all elements have inverses
2. $\mathbb{K}$ induces a **product by scalars** upon $V$ (resembles a [[Group Action]] but from the field $\mathbb{K}$)
	- The product of scalars with vectors is commutative ($(\mu \nu) \cdot v = (\nu \mu) \cdot v$) and associative ($(\mu\nu) \cdot (\rho \cdot v) = \mu \cdot ((\nu \rho) \cdot v)$)
3. The sum and product operations are both distributive
	- $(\mu + \nu) \cdot v = \mu \cdot v + \nu \cdot v$
	- $\mu \cdot (u + v) = \mu \cdot u + \mu \cdot v$

# Properties
Every vector space can be seen as an [[Affine Space]], via the [[Canonical Affine Structure of  a Vector Space]].

---
### References
- [abstract algebra - What is a "field action", and how does it relate to group actions? - Mathematics Stack Exchange](https://math.stackexchange.com/questions/4655709/what-is-a-field-action-and-how-does-it-relate-to-group-actions)