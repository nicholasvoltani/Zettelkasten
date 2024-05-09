---
Date: 2023-06-26
Tags: mathematics
alias: Homomorphism
---
up:: [[Group (Mathematics)]]

A function $\varphi: G \to G'$ between groups $(G, \cdot_G)$ and $(G', \cdot_{G'})$ is said to be a homomorphism if it preserves both groups' operations. 

That is,
$$
\forall g, h \in G: \varphi(g \cdot_G h) = \varphi(g) \cdot_{G'} \varphi(h)
$$

# Corollaries
1. Homomorphisms preserve neutral elements: $\varphi(g) = \varphi(g e_G) = \varphi(g) \varphi(e_G) \implies e_{G'} = \varphi(e_G)$
2. Homomorphisms preserve inverse operations: $\varphi(g) \varphi(g)^{-1} = e_{G'} = \varphi(g g^{-1}) = \varphi(g) \varphi(g^{-1}) \implies \varphi(g^{-1}) = \varphi(g)^{-1}$ 

---
# References
- [Group homomorphism - Wikipedia](https://en.wikipedia.org/wiki/Group_homomorphism)