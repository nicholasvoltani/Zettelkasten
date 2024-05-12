---
date: 2024-02-02
tags:
  - mathematics
aliases:
---
up:: [[023 MOC Measure Theory]]

Given a set $X$, a $\sigma$-algebra over $X$ $\mathcal{F} \subseteq \mathcal{P}(X)$ such that
- $X \in \mathcal{F}$
- **Closed under intersection**: $\forall A, B \in \mathcal{F}: A \cap B \in \mathcal{F}$
- **Closed under countable unions**: $\forall \{A_n\}_{n \in \mathbb{N}} \subseteq \mathcal{F}: \bigcup\limits_{n \in \mathbb{N}} A_n \in \mathcal{F}$ 

# Properties
- $\emptyset \in \mathcal{F}$;
- $\mathcal{F}$ is also closed under countable intersections
- Elements of $\mathcal{F}$ are called **measurable sets** (since they are allowed to be measured via a [[Measure (function)]])

---
### References
- [σ-algebra - Wikipedia](https://en.wikipedia.org/wiki/%CE%A3-algebra#Definition)