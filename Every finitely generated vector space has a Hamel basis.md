---
Date: 2023-07-27
Tags: mathematics
alias: 
---
up:: [[Finitely Generated Vector Space]]

Let $(V, +,\cdot)$ be a finitely generated vector space. Then it has, per definition, a finite [[Spanning Set]][^1] $S = \{s_1, \dots, s_m\} \subset V$. 

Then we can construct a basis from zero:
- Let $v_1 \neq 0$. Then $\{v_1\}$ is [[Linear Independence|Linearly Independent]]. If it generates $V$, then done.
- If it doesn't generate $V$, let $v_2 \notin [v_1]$, which implies that $\{v_1, v_2\}$ is linearly independent. If it generates $V$, done. Else, repeat.

Since [[Every linearly independent set of a finitely generated vector space has at most the same number of vectors as its spanning set]], this process terminates, at most, with $m$ vectors (the size of $S$). 

Thus, a set $B$ constructed in this fashion will be a [[Hamel Basis]], since it'll span $V$ and also be linearly independent.

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho & Mary Lilian Lourenço. Editora EDUSP.

[^1]: Note that it need not be linearly independent!