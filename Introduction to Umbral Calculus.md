---
Date: 2022-08-04
tags:
  - mathematics
publish: "true"
---
# Definition: Discrete Derivative (or Forward Difference Operator)
Given $f: \mathbb{Z} \to \mathbb{R}$, define
$$
\Delta f(n) := f(n+1) - f(n)
$$
which is "as infinitesimal" as the domain can get.

### Examples
$$
\begin{align}
\Delta(n) = (n+1) - n &= 1\\
\Delta (n^2) = (n+1)^2 - n^2 &= 2n + 1\\
\Delta(n^3) = (n+1)^3 - n^3 &= 3n^2 + 3n + 1\\
\vdots\\
\Delta(n^k) = (n+1)^k - n^k &= k n^{k-1} + \mathrm{etc}
\end{align}
$$
which follow like a Pascal's triangle. Let $c^m_k$ ($k \leq m$) be the coefficient multiplying the $k$-th power of the discrete derivative of $n^m$. Then:

$$
\begin{align*}
\Delta(n) = 1 n^0& = c^0_0\\
\Delta(n^2) = 2n^1 &+ 1n^0 = c^1_1 n^1 + c^1_0 n^0\\
\Delta(n^3) = 3n^2 &+ 3n^1 + 1n^0 = c^2_2 n^2 + c^2_1 n^1 + c^2_0 n^0\\
\Delta(n^4) = 4n^3 &+ 6n^2 + 4n^1 + 1n^0 = c^3_3 n^3 + c^3_2 n^2 + c^3_1 n^1 + c^3_0 n^0\\
\vdots
\end{align*}
$$


Then (for $m > 2$)
$$
\Delta(n^m) = m n^{m-1} + \sum\limits_{l = 1}^{m-2}(c^{m-1}_l + c^{m-1}_{l-1}) n^l + 1
$$

Note that it's the same relation as in the Pascal triangle[^1], for which
$$
\pmatrix{m\\l} = \pmatrix{m-1\\l} + \pmatrix{m-1\\l-1}
$$

# Definition: Falling Factorial
For $n, k \in \mathbb{N}$, define 
$$
n^{\underline{k}} := \prod\limits_{l = 0}^{k-1} (n-l) = n (n-1) (n-2) \dots (n- k+1)
$$
Note that
$$
n^{\underline{k}} = k! \begin{pmatrix} n\\ k \end{pmatrix}
$$


### Examples
$$
\begin{align}
n^{\underline{0}} &= 1\\
n^{\underline{1}} &= n\\
n^{\underline{2}} &= n^2 - n\\
\vdots\\
n^{\underline{k}} &= n^k + \mathrm{etc}
\end{align}
$$

# Theorem 1: Discrete derivative for falling factorials = Calculus for natural powers
For $n, k \in \mathbb{N}$, we have
$$
\Delta n^{\underline{k}} = k n^{\underline{k-1}}
$$
**Proof:**
$$
\begin{align}
\Delta n^{\underline{k}} &= (n+1)^{\underline{k}} - n^{\underline{k}}\\
&=  ({\color{blue} n+1}) ({\color{blue}n+1}-1) ({\color{blue}n+1}-2) \dots ({\color{blue} n +1}- k+2) ({\color{blue} n +1}- k+1) - n (n-1) (n-2) \dots (n- k+1)\\
&= (n+1) \underbrace{n (n-1) (n-2) \dots (n+1 - (k-1))} - \underbrace{n (n-1) \dots (n- k + 2)} (n - (k-1))\\
&= \underbrace{n (n-1) \dots (n- k + 2)} \left[n+1 - (n-k+1)\right]\\
&= kn^{\underline{k-1}}  
\end{align}
$$
In a more elucidative form:
$$
\begin{align}
\Delta n^{\underline{k}} &= (n+1)^{\underline{k}} - n^{\underline{k}}\\
&= k! \left(\begin{pmatrix} n+1\\ k \end{pmatrix} - \begin{pmatrix} n\\ k \end{pmatrix}\right)\\
&= k! \begin{pmatrix} n\\ k-1 \end{pmatrix}\\
&= k (k-1)! \begin{pmatrix} n\\ k-1 \end{pmatrix}\\
&= k n^{\underline{k-1}}
\end{align}
$$
(Third line is Pascal's Triangle's relationship)

# Derivative of Exponential Functions
Given $0 \neq a \in \mathbb{R}$, we have (let $f: \mathbb{N} \to \mathbb{R} \mid f(n) = a^n$)
$$
\Delta a^n = a^{n+1} - a^n = (a-1) a^n
$$
Note that it follows that
$$
\Delta 2^n = 2^n
$$

# Definition: Discrete Antiderivative
Given $g, G: \mathbb{Z} \to \mathbb{R}$, we say that $G$ is the antiderivative of $g$ if
$$
\Delta G(n) = g(n)
$$
Denote the antiderivative operator as 
$$
\sum g(n) = G(n)
$$
## Corollaries: Antiderivative of falling factorials and real numbers
$$
\sum n^{\underline{k}} = \frac{1}{k+1} n^{\underline{k+1}}
$$
$$
\sum a^n = \frac{1}{a-1} a^n
$$

## Example: Fibonacci numbers!
$F_0 = 0, F_1 = 1, F_{n+1} = F_{n} + F_{n-1}$.

Observe that 
$$
\Delta F_n = F_{n+1} - F_n = F_{n-1}
$$
and so it acts as a "step-down" operator.

Likewise, the discrete antiderivative acts as a "step-up" operator, since it yields the function that, when derived, results in $F_n$ (i.e. $F_{n+1}$):
$$
\sum F_n = F_{n+1}
$$
## Theorem 2: Discrete Fundamental Theorem of Calculus
Given $g, G: \mathbb{Z} \to \mathbb{R}$, where $G$ is the antiderivative of $g$. Then
$$
\sum\limits_{n=a}^b g(n) = G(b+1) - G(a)
$$
**Proof:** It's essentially a telescopic sum. Note that the same proof sketch appears in the Fundamental Theorem of Calculus, and even in Stokes' Theorem.
$$
\begin{align}
\sum\limits_{n=a}^b g(n) &= \sum\limits_{n=a}^b \Delta G(n)\\
&= \sum\limits_{n=a}^b (G(n+1) - G(n))\\
&= (G(b+1) - G(b)) + (G(b) - G(b-1)) + \dots + (G(a+1) - G(a))\\
&= G(b+1) - G(a)
\end{align}
$$
Note that it's essentially the same as the fundamental theorem of calculus, except for the $+1$, which is analogous to an infinitesimal $dx$: all natural numbers are **at least** 1 unit apart from each other, which doesn't really happen in the real numbers (nor in the rationals), since it's a dense set. 

## Product Rule for Discrete Derivative
$$
\Delta ((f\cdot g)(n) ) = \Delta f(n) g(n) + f(n) \Delta g(n) + \Delta f(n) \Delta g(n)
$$
**Proof:**
$$
\begin{align}
\Delta ((f\cdot g)(n)) &= f(n+1) g(n+1) - f(n)g(n) \pm f(n+1)g(n)\\
&= f(n+1) \cdot (g(n+1) - g(n)) + (f(n+1) - f(n))\cdot g(n)\\
&= f(n+1) \Delta g(n) + \Delta f(n) g(n)\\
&= (\Delta f(n) + f(n)) \Delta g(n) + \Delta f(n) g(n)\\
&= \Delta f(n) g(n) + f(n) \Delta g(n) + \Delta f(n) \Delta g(n)
\end{align}
$$
Note that the term $\Delta f(n) \Delta g(n)$ appears here, and not in regular Calculus, since there is a $\lim\limits_{dx \to 0} f(x + dx) \frac{g(x+dx)}{dx}$ in place. In Discrete Calculus, we can only go as close as +1 from any integer, so these terms that would vanish in Standard Calculus don't vanish here.

## Summation by Parts
$$
\sum\limits_a^b f(n) \Delta g(n) = f(b+1) g(b+1) - f(a) g(a) - \sum\limits_a^b \Delta f(n) g(n+1)
$$

**Proof**:
$$
\begin{align}
\sum\limits_a^b f(n) \Delta g(n) &= \sum\limits_a^b \left(\Delta (f \cdot g)(n) - \Delta f(n) g(n) - \Delta f(n) \Delta g(n)\right)\\
&= \sum\limits_a^b \Delta (f \cdot g)(n) - \sum\limits_a^b \Delta f(n) \left(g(n) + \Delta g(n)\right)\\
&= f(b+1) g(b+1) - f(a) g(a) - \sum\limits_a^b \Delta f(n) g(n+1)\\
&= [f(n)]_a^b - \sum\limits_a^b \Delta f(n) g(n+1)
\end{align}
$$

Note that it's very similar to its analogue in Differential Calculus, in which
$$
\int_a^b f(x) \partial g(x) dx = f(b) g(b) - f(a) g(a) - \int_a^b \partial f(x) g(x) dx
$$

# Applications: Evaluating (some) series!
$$
\begin{align*}
\sum\limits_1^N n &= [n\cdot n]_1^{N+1} - \sum\limits_1^N 1 \cdot (n+1)\\
&= (N+1)^2 - 1 - \sum\limits_1^N 1 \cdot (n+1) \pm 1\\
&= N^2 + N - \sum\limits_1^N n\\
\therefore \sum\limits_1^N n &= \frac{N (N+1)}{2}
\end{align*}
$$


---
### Referências
- <https://www.youtube.com/watch?v=FNh-Xkfnu1M>

[^1]: Check Wikipedia's article on [Pascal's Triangle](https://en.wikipedia.org/wiki/Pascal%27s_triangle).