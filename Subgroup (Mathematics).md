---
Date: 2023-06-26
Tags: mathematics
alias: Subgroup
---
up:: [[Group (Mathematics)]]

Given a group $(G, \cdot)$ and a subset $H \subset G$, then $(H, \cdot)$ is a subgroup of $G$ if it is a group in its own right under the restricted operation $\cdot\mid_H: H \times H \to G$. That is, $H$ is closed under the group operation. Thus, the following properties must hold:
1. **Closed under operation**: $\forall h, h' \in h, h\cdot h' \in H$
2. **Existence of neutral element**: $\exists e_H \in H \mid \forall h \in H, h \cdot e_H = e_H \cdot h = h$
3. **Existence of inverse element**: $\forall h \in H, \exists h^{-1} \in H \mid h \cdot h^{-1} = h^{-1} \cdot h = e_H$

One denotes $H \leq G$ as a shorthand for $H$ being a subgroup of $G$.

# Corollaries
The subgroup test can be simplified as 
$$\forall h, k \in H, hk^{-1} \in H$$

1. $e_H = e_G$, since $h \in H \implies e_H = h \cdot h^{-1} = e_G$

---
### References
- [Subgroup - Wikipedia](https://en.wikipedia.org/wiki/Subgroup)