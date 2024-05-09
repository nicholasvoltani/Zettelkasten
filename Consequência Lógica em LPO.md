---
Date: 2021-08-26
Tags: mathematics 
---
## Definição: Satisfação/*Entailment*/Consequência Lógica
Dada uma interpretação $\mathfrak{I}$ e uma *lookup table* $\mu$, dizemos que uma fórmula $\alpha$ é **satisfeita** na interpretação $\mathfrak{I}$ (e que escrevemos como $\mathfrak{I}, \mu \models \alpha$ segundo Levesque, e $\mathfrak{I} \models_\mu \alpha$ segundo Huth) de acordo com as seguintes fórmulas:
- Dados termos $(t_1, \dots, t_n)$ e predicado $n$-ário $P$, então
$$
\mathfrak{I}, \mu \models P(t_1, \dots, t_n) \iff (\|t_1\|, \dots, \|t_n\|) \in \mathcal{I}[P]
$$
- $\mathfrak{I}, \mu \models (t_1 = t_2) \iff \|t_1\|_{\mathfrak{I}, \mu} = \|t_2\|_{\mathfrak{I}, \mu} \,\,(\in D)$
- $\mathfrak{I}, \mu \models \lnot \alpha \iff$ it's false that $\mathfrak{I}, \mu \models \alpha$;
- $\mathfrak{I}, \mu \models (\alpha \land \beta) \iff$ $\mathfrak{I}, \mu \models \alpha$ **e** $\mathfrak{I}, \mu \models \beta$
- $\mathfrak{I}, \mu \models (\alpha \lor \beta) \iff$ $\mathfrak{I}, \mu \models \alpha$ **ou** $\mathfrak{I}, \mu \models \beta$
- $\mathfrak{I}, \mu \models \exists x.\alpha \iff \exists \mu' \mid \mathfrak{I}, \mu' \models \alpha$ para alguma *lookup table* que **difira** de $\mu$ em **no máximo $x$**
- $\mathfrak{I}, \mu \models \forall x.\alpha \iff \forall \mu' \mid \mathfrak{I}, \mu' \models \alpha$ para qualquer *lookup table* que **difira** de $\mu$ em **no máximo $x$**

Como sentenças $\alpha$ são fórmulas **sem variáveis livres**, elas são invariantes a *variable assignments* $\mu$. Por isso, escrevemos que 
$$
\mathfrak{I} \models \alpha
$$
quando quisermos dizer que $\alpha$ é **verdadeiro sob a interpretação $\mathfrak{I}$**, e que é **falso** caso contrário. São as sentenças que serão as unidades de conhecimento em uma base de conhecimento. 


## Referências
- BRACHMAN, Ronald J.; LEVESQUE, Hector J.; REITER, Raymond (Ed.). **Knowledge representation**. MIT press, 1992.
- HUTH, Michael; RYAN, Mark. **Logic in Computer Science: Modelling and reasoning about systems**. Cambridge university press, 2004.
