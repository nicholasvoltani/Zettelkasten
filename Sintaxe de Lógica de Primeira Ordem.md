---
Date: Tuesday, 24-08-2021 @ 21:07
Tags:
---
# Sintaxe de Lógica de Primeira Ordem
É composta tanto de símbolos lógicos quanto não-lógicos:
- Símbolos lógicos: 
	- **Pontuação**: "(", ")", ".";
	- **Conectivos**: $\lnot$, $\land$, $\lor$, $\forall$, $\exists$, $=$
		- Definição: $(\alpha \supset \beta) \equiv (\lnot \alpha \lor \beta)$;  $(\alpha \equiv \beta) \equiv ((\alpha \supset \beta) \land (\beta \supset \alpha))$
	- **Variáveis**: $x, y, z, \cdots$
- Símbolos não-lógicos (*nonlogical symbols*):
	- Símbolos de **função**: $f, g, \dots$ tais que $f: \Omega^n \to \Omega$
	- Símbolos de **predicado**: $P, Q, \dots$ tais que $P: \Omega^n \to \{0, 1\}$
Esses $n$'s em $\Omega^n$ denotam a *aridade* desses operadores: unários, binários, etc. 

# Termos e fórmulas (bem-definidas)
## Definição: Termos
O conjunto de *termos* é o conjunto mínimo que satisfaz as seguintes regras:
- Toda variável $x, y, \dots$ é um termo;
- Dados $(t_1, \dots, t_n)$ termos, e $f$ uma função $n$-ária, então $f(t_1, \dots, t_n)$ é também um termo.

## Definição: Fórmulas (bem-definidas)
O conjunto de *fórmulas (bem-definidas)* é o conjunto mínimo que satisfaz as seguintes regras:
- Dados $(t_1, \dots, t_n)$ termos, e $P$ um predicado $n$-ário, então $P(t_1, \dots, t_n)$ é também uma fórmula;
- Dados $t_1, t_2$, temos que $t_1 = t_2$ é uma fórmula;
(As regras acima definem o que se chamam **funções atômicas**/**átomos**.)
- Dadas fórmulas $\alpha, \beta$ e uma variável $x$, então $\lnot \alpha$, $(\alpha \land \beta)$, $(\alpha \lor \beta)$, $\forall x.\alpha$, $\exists x. \alpha$. 

---
### References
- BRACHMAN, Ronald J.; LEVESQUE, Hector J.; REITER, Raymond (Ed.). **Knowledge representation**. MIT press, 1992.