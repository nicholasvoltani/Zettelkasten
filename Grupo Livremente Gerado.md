---
Date: Sunday, 15-08-2021 @ 23:42
Tags:
---
# Grupo Livremente Gerado por conjunto $X$
Dado um conjunto $X$, definimos o **grupo livremente gerado** $F(X)$ como
$$F(X) \equiv \{f: X \to \mathbb{Z} \mid |supp(f)| < \infty\}$$
o conjunto das funções $f: X \to \mathbb{Z}$ de suporte finito, com a operação de grupo 
$$f, g \in F(X) \implies (f+g)(x) \equiv f(x) + g(x)$$


## Decomposição em funções características
Cada elemento $f \in F(X)$ pode ser decomposto numa combinação linear de funções características
$$f = \sum\limits_{i=1}^N a_i \delta_{x_i}$$
onde 
$$\begin{align*}
	\delta_x(y) = \begin{cases}
	 1, \, x = y\\
	0, \, x \neq y
	\end{cases}
\end{align*}$$

## $F(X)$ é grupo sob soma
1. Dados $f, g \in F(X)$, com suportes $supp_f, supp_g$, a soma $f+g$ terá suporte $supp_f \cup supp_g$ (ou seja, está em $F(X)$). 

2. $0: X \to \mathbb{Z}$ é o elemento neutro (possui suporte vazio).

3. O elemento inverso se define como $f = \sum\limits_{i=1}^N a_i \delta_{x_i} \iff (-f) \equiv \sum\limits_{i=1}^N (-a_i) \delta_{x_i}$. 