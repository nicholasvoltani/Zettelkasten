---
Date: 2023-10-07
tags:
  - physics
---
up:: [[Newton's Third Law]]

Given a system of particles $\{m_i\}$, with reciprocal forces $\{\vec{F}_{i\to j}\}_{i, j\neq i}$, we have that these forces can be seen as an antisymmetrical matrix
$$
A = \begin{pmatrix}
0 & F_{1 \to 2} & \dots &F_{1 \to n}\\
-F_{1 \to 2} & 0 & \dots & F_{2 \to n}\\
\vdots & \vdots & \ddots & \vdots\\
-F_{1 \to n} & -F_{2 \to n} & \dots & 0
\end{pmatrix}
$$
The sum of these reciprocal forces is the sum of all elements of $A$,
$$\sum\limits_{\substack{i, j\\ i \neq j}}^n F_{i \to j} = \sum\limits_{\substack{i, j\\ i \neq j}}^n A_{ij} = 0$$
which has to be $0$.

# Corollaries
- [[Linear Momentum Conservation Theorem]], which states that the [[Center of Mass]] behaves like a particle under the influence of (the sum of) all external forces