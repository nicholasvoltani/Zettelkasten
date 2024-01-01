---
Date: 2023-07-05
tags:
  - physics
aliases:
  - Only external forces influence a center of mass's momentum
---
up:: [[Classical Linear Momentum|Linear Momentum]]

Let $\{r_i\}_{i=1}^n$ be the positions of particles $i$, of mass $\{m_i\}_{i=1}^n$, with [[Center of Mass]] $\vec{R}$ and external forces $\{F_i^{(e)}\}$. Then
$$M \frac{d^2\vec{R}}{dt^2} = \sum\limits_{i=1}^n\vec{F}^{(e)}_i$$
That is, the sum of the **external forces** over a system of particles induces Newton's Second Law to the **equivalent particle** $(M, \vec{R})$, located at the center of mass and with mass equal to the system's total mass.

# Proof
By [[Newton's Second Law]], we have that, for each particle $i$[^2], 
$$\frac{d\vec{p_i}}{dt} = \sum\limits_{\substack{j=1\\j\neq i}}^n \vec{F}_{j \to i} + \vec{F}^{(e)}_i$$
Summing for all particles $j$, we have that
$$\sum\limits_i \frac{d\vec{p_i}}{dt} = \sum\limits_{\substack{i, j=1\\j\neq i}}^n \vec{F}_{j \to i} + \sum\limits_{i=1}^n\vec{F}^{(e)}_i$$

Due to [[Newton's Third Law]], $\sum\limits_{\substack{i, j=1\\j\neq i}}^n \vec{F}_{j \to i} = \vec{0}$[^1]. Thus,
$$\sum\limits_i m_i \frac{d \vec{p_i}}{dt} = \sum\limits_{i=1}^n\vec{F}^{(e)}_i$$
Using the [[Center of Mass]] definition, and supposing that $\frac{d m_i}{dt} = 0$, one can write the above as
$$\sum\limits_{i=1}^n\vec{F}^{(e)}_i = M \frac{d^2\vec{R}}{dt^2}$$
# Corollaries
[[A system's total momentum is conserved if it has no net external forces]]: If the external forces sum to $\vec{0}$, then **the system's total momentum**
$$\vec{P} = \sum\limits_{i=1}^n m_i v_i = \sum\limits_{i=1}^n m_i \frac{d\vec{r}_i}{dt} = M \frac{d\vec{R}}{dt}$$
**is conserved**.

## Examples
Let a system of two particles with no external forces acting upon them. Then
$$m_1 \vec{v_1} = m_2 \vec{v_2}$$

---
### References
- LEMOS, Nivaldo A. **Mecânica analítica**. Editora Livraria da Física, 2007.

[^1]: [[The sum of all reciprocal forces in a system of particles is always zero]]. One can think about it as summing all values of an antisymmetric matrix.
[^2]: Denoting $F_{j \to i}$ as the force the particle $j$ exerts upon particle $i$.