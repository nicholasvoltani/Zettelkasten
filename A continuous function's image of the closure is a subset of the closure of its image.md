---
Date: 2023-07-03
Tags: mathematics
---
up:: [[Topologically Continuous Function]]

Given a [[Topologically Continuous Function]] $f: (X, \tau_X) \to (Y, \tau_Y)$, it can be proven that [[Continuous functions premap closed sets to closed sets]] is equivalent to the assertion that, for each $D \subseteq X$, the function satisfies that
$$
f(\overline{D}) \subseteq \overline{f(D)}
$$

# "Thesis" implies usual definition
Assuming that $f(\overline{D}) \subseteq \overline{f(D)}$, we seek to prove that $f^{-1}(F) \in \mathcal{F}(\tau_X)$, for any closed set $F \in \mathcal{F}(\tau_Y)$.

Let $F \in \mathcal{F}(\tau_Y)$ a closed set. Considering $f^{-1}(F) \subseteq X$, per hypothesis, $f(\overline{f^{-1}(F)}) \subseteq \overline{f(f^{-1}(F))}$.

Using [[The image of the preimage of a set is contained in the set]] ($f(f^{-1}(F)) \subseteq F$) and that [[Closure preserves subset ordering]] yields
$$
f(\overline{{\color{green}f^{-1}(F)}}) = \overline{f({\color{green}f^{-1}(F)})} \subseteq \overline{{\color{green} F}} = {\color{green} F}
$$
Taking the preimage on both sides (using that [[Preimages preserve subset ordering]]), since [[The preimage of the image of a set contains the set]] ${\color{green}f^{-1}(F)} \subseteq f^{-1}({\color{green}f(f^{-1}(F))})$, we have that
$$
\overline{f^{-1}(F)} \subseteq f^{-1}(F)
$$
Since [[All sets are contained inside their closure]], it is proved that $f^{-1}(D) = \overline{f^{-1}(D)}$, thus $f^{-1}(D)$ is closed, and therefore $f$ premaps closed sets (in $Y$) to closed sets (in $X$).

# Usual definition implies "thesis"
Let $f$ be continuous in the usual sense, i.e. premap closed sets in $Y$ to closed sets in $X$. 

Let $D \subseteq X$ be some arbitrary set. Since [[The preimage of the image of a set contains the set]] and that [[All sets are contained inside their closure]], we have that
$$
D \subseteq f^{-1}(f(D)) \subseteq f^{-1}(\overline{f(D)})
$$
Since $f^{-1}(F) \in \mathcal{F}(\tau_X)$ for any closed set in $Y$ per hypothesis, and using that [[Closure preserves subset ordering]], then we can take the [[Closure (Topology)|Closure]] on both sides, yielding
$$
\overline{D} \subseteq f^{-1}(\overline{f(D)})
$$
Using that [[Function images preserve subset ordering]], we have that
$$
f(\overline{D}) \subseteq f\left(f^{-1}\left({\color{green} \overline{f(D)}}\right)\right)
$$

Then, using that [[The image of the preimage of a set is contained in the set]] for the set $\color{green} \overline{f(D)}$, we have 
$$
f(\overline{D}) \subseteq f\left(f^{-1}\left({\color{green} \overline{f(D)}}\right)\right) \subseteq {\color{green} \overline{f(D)}}
$$

Thus, all [[Topologically Continuous Function]]s (in the usual definition) satisfy this property. 


---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 30](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap30.pdf)