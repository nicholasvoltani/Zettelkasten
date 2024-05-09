---
Date: 2024-02-02
tags:
  - mathematics
aliases:
  - Probability
---
up:: [[023 MOC Measure Theory]]

A probability function is a function defined from the [[Sigma-algebra]] of a [[Measurable Space]] $(X, \mathcal{F})$ to the real numbers, $P: \mathcal{F} \to \mathbb{R}$ which satisfies
- $\forall A \in \mathcal{F}: P(A) \geq 0$;
- $P(X) = 1$
- For a countable set of **mutually disjoint** measurable sets $\{A_n\}_{n \in \mathbb{N}}$, we have 
$$
P\left(\bigcup\limits_{n \in \mathbb{N}}A_n\right) = \sum\limits_{n \in \mathbb{N}} P(A_n)
$$
# Properties
- $\forall A \in \mathcal{F}: P(A^c) = 1 - P(A)$[^1]
- $P(\emptyset) = 0$
- $\forall A \subseteq B \in \mathcal{F}: P(A) \leq P(B)$[^2]
	- $\forall A \in \mathcal{F}: 0 \leq P(A) \leq P(1)$
- $\forall A, B \in \mathcal{F}: P(A \cup B) = P(A) + P(B) - P(A \cap B)$[^3]
- [[Continuity Theorem of Probabilities over (non-)decreasing sets of events]]

---
### References
- 

[^1]: Since $C = A \cup A^c$, and since $P(A) + P(A^c) = 1$.
[^2]: Note that $B = A \cup (A^c \cap B)$ of disjoint sets; thus, $P(B) = P(A) + P(\dots) \geq P(A)$.
[^3]: Note that ${\color{red} A} \cup B = {\color{red} A} \cup (B \setminus A) = {\color{red} A} \cup (B \cap A^c)$ and $B = (B \setminus A) \cup A = (B \cap A^c) \cup (B \cap A)$.