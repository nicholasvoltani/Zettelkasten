---
Date: 2023-07-11
Tags: mathematics
alias: G-Torsor
---
up:: [[021 MOC Algebra]]

> "A torsor is like a group that has forgotten its identity." (John Baez)

In a $G$-torsor, one cannot add elements ─ but rather, one can think of their **differences** as being elements of an underlying group $G$.

A $G$-torsor is a set $T$ with a [[Group Action]] over some [[Group (Mathematics)|Group]] $G$
$$
+: G \times T \to T
$$
which is [[Free Group Action|Free]] and [[Transitive Group Action|Transitive]]. This means that every pair of points in $T$ has only one element in $G$ which "connects" them ─ which can be seen as their **difference** (or **ratio**).

# Examples
- An [[Affine Space]] is an example of an $\mathbb{R}^n$-torsor ─ we can only measure real position **differences**
- Energies lie in an $\mathbb{R}$-torsor ─ we can only measure real energy **differences**
- Voltages lie in an $\mathbb{R}$-torsor ─ we can only measure real voltage **differences**

---
### References
- [torsor in nLab](https://ncatlab.org/nlab/show/torsor)
- [torsors (John Baez)](https://math.ucr.edu/home/baez/torsors.html)