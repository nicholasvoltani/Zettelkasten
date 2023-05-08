---
Date: Sunday, 15-08-2021 @ 23:27
Tags: mathematics 
---
# Definição de Subgrupo Normal
Dado um grupo $G$ e um subgrupo $N \leq G$, temos que $N$ é um **subgrupo normal** de $G$ (denotamos $N \trianglelefteq G$) se 
$$g^{-1} n g \in N, \forall g \in G, \forall n \in N$$

## Definição equivalente
Tal definição é equivalente a 
$$ng = gn, \forall g \in G, \forall n \in N \iff Ng = gN, \forall g \in G$$
ou seja, os *cosets* à esquerda de $N$, $gN$, são iguais aos cosets à direita $Ng$. 

## Equivalência ao *kernel* de um homomorfismo
Dado um homomorfismo $\varphi: G \to G'$, temos que o núcleo de $\varphi$ 
$$\ker \varphi = \{k \mid \varphi(k) = 0\}$$
é um subgrupo normal de $G$, pois
$$\forall g \in G, \forall k \in \ker \varphi, \,\, \varphi(g^{-1} k g) = e_G$$

A recíproca também é verdadeira: dados $N \trianglelefteq G$, podemos criar o homomorfismo
$$\begin{align}
\varphi:&  \, G \to G/N\\
&g \mapsto gN
\end{align}$$
cujo núcleo é $\ker \varphi = N$. 