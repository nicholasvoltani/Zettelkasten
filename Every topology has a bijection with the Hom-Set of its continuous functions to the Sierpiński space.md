---
Date: 2023-08-06
Tags: mathematics
alias: 
---
up:: [[Sierpiński Space]]

> Given a [[topological space]] $(Z, \tau)$, one can create a [[Bijective Function|Bijection]] between $\tau$ and the [[Hom-Set]] of all [[Topologically Continuous Function]]s $Hom(Z, S)$. 

Given any other topological space $(Z, \tau)$, for each open set $U \in \tau$, define $F: \tau \to Hom(Z, S)$ such that $F(U) := \chi_U$ is the characteristic function of this open set $U$ onto the [[Sierpiński space]] $(S, \tau_S)$:
$$\begin{align*}
\chi_U: &Z \to S\\
&z \mapsto \begin{cases}
1, z \in U\\
0, z \notin U
\end{cases}
\end{align*}
$$
Note that it is continuous, since, for every open set in $\tau_S$,
$$\begin{align*}
\chi_U^{-1}(\{0,1\}) &= Z \in \tau\\
\chi_U^{-1}(\{1\}) &= U \in \tau\\
\chi_U^{-1}(\emptyset) &= \emptyset \in \tau
\end{align*}
$$
Note that $F$ is [[Injective Function|Injective]], since different sets $U, V$ will necessarily have different characteristic functions.

Conversely, note that, for any continuous function $f: Z \to S$, it will have only one open set $U_f = f^{-1}(\{1\}) \in \tau$ associated to it. Note that this mapping $f \mapsto U_f$ is injective as well, else their preimages would be the same.

Thus, through the [[Cantor-Bernstein-Schroeder Theorem]], we conclude that there is a bijection between $\tau$ and $Hom(Z, S)$, where the open set $\{1\} \in \tau_S$ acts as the "indicator" for each open set $U_f \in \tau$ under the continuous function $f: Z \to S$.


---
### References
- [The Sierpinski Space and Its Special Property](https://www.math3ma.com/blog/the-sierpinski-space-and-its-special-property)