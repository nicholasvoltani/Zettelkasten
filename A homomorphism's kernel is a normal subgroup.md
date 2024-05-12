---
date: 2023-06-26
tags:
  - mathematics
---
up:: [[Normal Subgroup]]

Given a [[Group Homomorphism]] $\varphi: G \to G'$, then this homomorphism's [[Kernel (Group)]] is a normal subgroup of $G$. 

Let $K := \ker\varphi$. Then we seek to prove

Let $g \in G$ and $k \in K$. Then
$$
\varphi(g^{-1} n g) = \varphi(g)^{-1} \varphi(k) \varphi(g) = \varphi(g)^{-1} \varphi(g) = e_{G'}
$$
Thus, $g^{-1} n g \in K$.

SInce it holds that
$$
\forall g \in G, \forall k \in K: g^{-1} k g \in K
$$
then $K$ is a normal subgroup of the domain of $\varphi$.