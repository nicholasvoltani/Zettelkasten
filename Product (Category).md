---
date: 2023-08-21
tags:
  - mathematics
alias: Product
---
up:: [[028 MOC Category Theory]]

![[Pasted image 20230821211433.png|300]]

Given a [[Category]] $C$, and objects $X_1, X_2 \in Ob(C)$, we have that their product $X_1 \times X_2$ is defined by the diagram above:
- For every $X_i$, there is a **projection morphism** $X_1 \times X_2 \overset{\pi_i}{\longrightarrow} X_i$
- If there is some other object $Y \in Ob(C)$ which has morphisms to the individual objects $Y \overset{f_i}{\longrightarrow} X_i$, then there is a **unique** morphism from it to the product $Y \overset{h}{\longrightarrow} X_1 \times X_2$
# Examples
- [[Cartesian products in Set are categorical products]]

---
### References
- MAC LANE, Saunders, **Categories for the Working Mathematician**, New York, NY: Springer New York, 1978.