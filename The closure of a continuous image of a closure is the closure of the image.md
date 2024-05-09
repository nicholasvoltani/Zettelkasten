---
Date: 2023-07-01
tags:
  - mathematics
alias: Continuous functions map close inputs to close outputs
---
up:: [[Topologically Continuous Function]]

> Continuous functions map close inputs to close outputs.

Given a [[Topologically Continuous Function|Topologically Continuous]] function $f: X \to Y$, it can be proven that, for any set $D \subseteq X$,
$$
\overline{f(\overline{D})} = \overline{f(D)}
$$
# $(\subseteq)$
Using that [[A continuous function's image of the closure is a subset of the closure of its image]] for a [[Topologically Continuous Function]] $f: (X, \tau_X) \to (Y, \tau_Y)$, one knows that, for any subset $D \subseteq X$,
$$
f(\overline{D}) \subseteq \overline{f(D)}
$$

From this, since [[Closure preserves subset ordering]], we have that 
$$
\overline{f(\overline{D})}  \subseteq \overline{f(D)}
$$
# $(\supseteq)$
On the other hand, since we know that [[All sets are contained inside their closure]], and that [[Function images preserve subset ordering]], we have that
$$
f(D) \subseteq f(\overline{D})
$$
Since [[Closure preserves subset ordering]], we also have that
$$
\overline{f(D)} \subseteq \overline{f(\overline{D})}
$$

# Conclusion
Thus, for all continuous functions, 
$$
\overline{f(\overline{D})} = \overline{f(D)}
$$

# Operators on the Power Set
We can see the image of $f$ and the closure $Cl$ as operators over power sets, as follows 
$$
\begin{cases}
Im_f: \mathbb{P}(X) \to \mathbb{P}(Y)\\
Cl_X: \mathbb{P}(X) \to \mathbb{P}(X)\\
Cl_Y: \mathbb{P}(Y) \to \mathbb{P}(Y) 
\end{cases}
$$

Using that, it can be observed that
$$
Cl_Y \circ Im_f \circ Cl_X = Cl_Y \circ Im_f \circ \mathbb{1}_{\mathbb{P}(X)}
$$

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 30](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap30.pdf)