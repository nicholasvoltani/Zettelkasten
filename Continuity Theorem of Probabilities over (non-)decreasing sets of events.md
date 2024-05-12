---
date: 2024-02-02
tags:
  - mathematics
aliases:
---
up:: [[Probability Function]]

> Probabilities commute with limits taken with respect to non-decreasing and decreasing sets of events.

# Proof for non-decreasing sets
Let $\{C_n\}_{n \in \mathbb{N}}$ be a non-decreasing sequence, i.e. $C_n \subseteq C_{n+1}$, "converging" to $\bigcup\limits_{n \in \mathbb{N}} C_n$. Then we seek to prove
$$
\lim\limits_{n \to \infty} P(C_n) = P\left(\lim\limits_{n \to \infty} C_n\right) = P\left(\bigcup_{n \in \mathbb{N}} C_n\right)
$$

For that, note that this sequence "grows radially" from $C_1$. For that, define "rings" to be
$$
\begin{cases}
R_1 \equiv C_1\\
R_{n+1} \equiv C_{n+1} \cap C_n^c 
\end{cases}
$$
1. With that, we see that $\bigcup C_n = \bigcup R_n$[^1]. 
2. Note also that $R_n \cap R_{n+1} = \emptyset$, and, thus, are all **mutually exclusive**.
3. Note that, since $P(A \cup B) =  P(A) + P(B) - P(A \cap B)$, we have that
$$
\begin{align}
P(R_{n+1}) &= P(C_{n+1} \cap C_n^c) = P(C_{n+1}) + (1 - P(C_n^c)) - \underbrace{P(C_{n+1} \cup C_n^c)}_{=1}\\
&= P(C_{n+1}) - P(C_n)
\end{align}
$$
Given all that, note that
$$
\begin{align}
P\left(\lim\limits_{n\to\infty} C_n\right) &= P\left(\bigcup_{n \in \mathbb{N}} C_n\right) = P\left(\bigcup\limits_{n \in \mathbb{N}} R_n\right)\\
&\overset{(2)}{=} \sum\limits_{n \in \mathbb{N}} P(R_n) \\
&\overset{(3)}{=} \lim\limits_{n \to \infty} \left[P(C_1) + \sum\limits_{n=2}^n (P(C_{n+1}) - P(C_n))\right]\\
&= \lim\limits_{n \to \infty} P(C_n)
\end{align}
$$

# Proof for decreasing sets
Let $\{D_n\}_{n \in \mathbb{N}}$ be a non-decreasing sequence, i.e. $D_n \supseteq D_{n+1}$, "converging" to $\bigcap\limits_{n \in \mathbb{N}} D_n$. Then we seek to prove
$$
\lim\limits_{n \to \infty} P(D_n) = P\left(\lim\limits_{n \to \infty} D_n\right) = P\left(\bigcap_{n \in \mathbb{N}} D_n\right)
$$
Note that $D_n \supseteq D_{n+1} \implies D_n^c \subseteq D_{n+1}^c$, we have
$$
\begin{align}
P\left(\lim\limits_{n\to\infty} D_n\right) &= P\left(\bigcap_{n \in \mathbb{N}} D_n\right) = 1 - P\left(\bigcup\limits_{n \in \mathbb{N}} D_n^c\right)\\
&=1 - \lim\limits_{n\to\infty}P(D_n^c) = \lim\limits_{n\to\infty}(1-P(D_n^c)) \\
&= \lim\limits_{n \to \infty} P(D_n)
\end{align}
$$

---
### References
- [Hogg, Robert V., Joseph W. McKean, and Allen T. Craig. Introduction to mathematical statistics. Pearson Education India, 2013.](https://minerva.it.manchester.ac.uk/~saralees/statbook2.pdf)

[^1]: Due to $R_1 = C_1$ and incrementing with these "excesses" $R_n$