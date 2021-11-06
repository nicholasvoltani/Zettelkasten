---
Date: Tuesday, 24-08-2021 @ 21:07
Tags:
---
# Sintaxe de Lógica de Primeira Ordem
É composta tanto de símbolos lógicos quanto não-lógicos:
- Símbolos lógicos (interpretação "fixa"): 
	- **Pontuação**: "(", ")", ".";
	- **Conectivos**: $\lnot$, $\land$, $\lor$, $\forall$, $\exists$, $=$
		- Definição: $(\alpha \supset \beta) \leftrightarrow (\lnot \alpha \lor \beta)$;  $(\alpha \equiv \beta) \leftrightarrow ((\alpha \supset \beta) \land (\beta \supset \alpha))$
	- **Variáveis**: $x, y, z, \cdots$
- Símbolos não-lógicos (*nonlogical symbols*; interpretação "variável"):
	- Símbolos de **função**: $f, g, \dots$ 
		- Funções de aridade 0 são chamadas de **constantes**.
	- Símbolos de **predicado**: $P, Q, \dots$
		- Predicados de aridade 0 são chamados de **símbolos proposicionais**.

## Termos e Fórmulas (bem-definidas)
### Definição: Termos ─ as "coisas"
O conjunto de *termos* é o **conjunto mínimo** que satisfaz as seguintes regras:
- Toda *variável* $x, y, \dots$ é um termo;
- Dados $(t_1, \dots, t_n)$ termos, e $f$ uma função $n$-ária (recebe $n$ termos), então $f(t_1, \dots, t_n)$ é também um termo (funções $0$-árias também são termos por definição).

### Definição: Fórmulas ─ as "asserções"
O conjunto de *fórmulas (bem-definidas)* é o **conjunto mínimo** que satisfaz as seguintes regras:
- Dados $(t_1, \dots, t_n)$ termos, e $P$ um predicado $n$-ário (recebe $n$ termos), então $P(t_1, \dots, t_n)$ é também uma fórmula;
- Dados $t_1, t_2$, temos que $t_1 = t_2$ é uma fórmula;
(As regras acima definem o que se chamam **funções atômicas**/**átomos**.)
- Dadas fórmulas $\alpha, \beta$ e uma variável $x$, então $\lnot \alpha$, $(\alpha \land \beta)$, $(\alpha \lor \beta)$, $\forall x.\alpha$, $\exists x. \alpha$ são também fórmulas. 

## Definição: Escopo de Variáveis
$$\begin{align}
\forall y. P\underbrace{(x)}_{\text{livre}} \land \exists \underbrace{x. [P(x) \lor Q(x)]}_{\text{Bound}}
\end{align}$$

## Definição: Sentença
Qualquer **fórmula** sem variáveis livres é chamada de **sentença**. 

Por exemplo:
$$\forall x. \, P(x) \lor Q(x)$$
é uma sentença, mas
$$\forall x. \, R(y)$$
não é. 


---
### References
- BRACHMAN, Ronald J.; LEVESQUE, Hector J.; REITER, Raymond (Ed.). **Knowledge representation**. MIT press, 1992.