---
Date: 2023-07-01
Tags: mathematics
---
up:: [[Topologically Continuous Function]]

Given a [[Topologically Continuous Function]] $f: (X, \tau_X) \to (Y, \tau_Y)$, it can be proven that [[Continuous functions premap closed sets to closed sets]] is equivalent to the assertion that, for each $D \subseteq X$, the function satisfies that
$$f(\overline{D}) \subseteq \overline{f(D)}$$

# $(\implies)$
Let $F \in \mathcal{F}(\tau_Y)$ a closed set in $Y$. We seek to prove that $f^{-1}(F) \in \mathcal{F}(\tau_X)$.

Assuming that $f(\overline{D}) \subseteq \overline{f(D)}$, and using ${\color{green} F = f^{-1}(D)}$, we have that, using [[The image of the preimage of a set is contained in the set]] and that [[Closure preserves subset ordering]],
$$f(\overline{{\color{green}f^{-1}(D)}}) = \overline{f(f^{-1}({\color{green} F})} \subset \overline{{\color{green} F}} = {\color{green} F}$$
Using that [[Preimages preserves subset ordering]], we have that
$$\overline{f^{-1}(D)} \subseteq f^{-1}(F)$$
Since [[All sets are contained inside their closure]], it is proved that $f^{-1}(D) = \overline{f^{-1}(D)}$, thus $f^{-1}(D)$ is closed, and therefore $f$ premaps closed sets (in $Y$) to closed sets (in $X$).

# $(\impliedby)$
Let $f$ be continuous in the usual sense, i.e. premap closed sets in $Y$ to closed sets in $X$. 

Let $D \subseteq X$ be some arbitrary set. Since [[The preimage of the image of a set contains the set]] and that [[All sets are contained inside their closure]], we have that
$$D \subseteq f^{-1}(f(D)) \subseteq f^{-1}(\overline{f(D)})$$
Since $f^{-1}(F) \in \tau_X$ for any closed set in $Y$, and using that [[Closure preserves subset ordering]], we have
$$\overline{D} \subseteq f^{-1}(f(D)) \subseteq f^{-1}(\overline{f(D)})$$
Using that [[Function images preserve subset ordering]], we have that
$$f(\overline{D}) \subseteq f\left(f^{-1}\left({\color{green} \overline{f(D)}}\right)\right)$$

Then, using that [[The image of the preimage of a set is contained in the set]] for the set $\overline{f(D)}$, we have 
$$f(\overline{D}) \subseteq f\left(f^{-1}\left({\color{green} \overline{f(D)}}\right)\right) \subseteq {\color{green} \overline{f(D)}}$$

Thus, all [[Topologically Continuous Function]]s satisfy this property. 

# Operators on the Power Set
We can see the image of $f$ and the closure $Cl$ as operators over the power set of $X$ to the power set of $Y$, as 
$$\begin{cases}
f: \mathbb{P}(X) \to \mathbb{P}(Y)\\
Cl_X: \mathbb{P}(X) \to \mathbb{P}(X)\\
Cl_Y: \mathbb{P}(Y) \to \mathbb{P}(Y) 
\end{cases}
$$

Using that, it can be observed that
$$f \circ Cl_X = Cl_Y \circ f$$

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 30](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap30.pdf)