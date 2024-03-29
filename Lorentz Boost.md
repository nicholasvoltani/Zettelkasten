---
Date: " 2024-01-11"
tags:
  - physics
aliases:
---
up:: [[033 MOC Relativity]]

A Lorentz Boost is a linear transformation of the type
$$\begin{cases}
ct' &= \gamma(ct - \beta \,x)\\
x' &= \gamma(x - \beta \, ct)
\end{cases} 
\iff 
\begin{pmatrix}
ct'\\x'
\end{pmatrix}
= 
\begin{pmatrix}
\gamma & -\gamma \beta\\
-\gamma \beta & \gamma
\end{pmatrix}
\begin{pmatrix}
ct\\x
\end{pmatrix}

 $$

where the boost can be seen as the (symmetric) matrix
$$\Lambda = \begin{pmatrix}
\gamma & -\gamma \beta\\
-\gamma \beta & \gamma
\end{pmatrix}$$
when only looking at a single-direction boost, in the $x$-direction.

# Matrix form in Minkowski Space
In Minkowski space, this boost (only in the $x$ direction) would be the matrix
$$\Lambda = \begin{pmatrix}
\gamma & -\gamma \beta &0 &0\\
-\gamma \beta & \gamma &0 &0\\
0 & 0 & 1 & 0\\
0 & 0 & 0 & 1
\end{pmatrix}$$
