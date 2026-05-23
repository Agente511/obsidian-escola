## Números complexos
O conjunto $\mathbb C$ é uma extensão de $\mathbb R$ que contém as raízes pares de números negativos.
### Operações
Designa-se por **corpo dos números complexos**, e representa-se por $\mathbb C$, o conjunto $\mathbb R^2$ munido das seguintes operações:
- $(a, b) \pm (c, d) = (a \pm c, b \pm d)$
- $(a, b) \times /(c, d) = (ac - bd, ad + bc)$

> [!Example] Propriedades das operações
> - ##### Comutatividade
> 	- $(a, b) + (c, d) = (c, d) + (a, b)$
> 	- $(a, b) \times (c, d) = (c, d) \times (a, b)$
> - ##### Associatividade
> 	- $[(a, b) + (c, d)] + (e, f) = (a, b) + [(c, d) + (e, f)]$
> 	- $[(a, b) \times (c, d)] \times (e, f) = (a, b) \times [(c, d) \times (e, f)]$
> - ##### Existência de elemento neutro
> 	- $(a, b) + (0, 0) = (a, b)$
> 	- $(a, b) \times (1, 0) = (a, b)$
> - ##### Distributividade da multiplicação em relação à adição
> 	$(a, b) \times [(c, d) + (e, f)] = (a, b) \times (c, d) + (a, b) \times (e, f)$

### Conjunto $\mathbb R$ como subconjunto de $\mathbb C$
Cada $x \in \mathbb R$ pode ser representado pelo elemento $(x, 0)$ de $\mathbb C$.
### Unidade imaginário $i$
Designa-se por unidade imaginária o número complexo $(0, 1)$, representado por $i$.

$\large i^2=-1 \iff i = \sqrt {-1}$

$i^2 = (0, 1) \times (0, 1) = (-1, 0)$

### Representação na forma algébrica
Dado um número complexo $z$, existem um único número real $a$ e um único número real $b$ tais que 

$\large z = a + bi$ $\ \ \ \longleftarrow$ forma algébrica
- $a$: **parte real de $z$** e representa-se por **Re$(z)$**
- $b$: **parte imaginário de $z$** e presenta-se por **Im$(z)$**

Um número complexo $z$ é
- **real** se e só se Im$(z)=0$
- **imaginário puro** se e só se Re$(z)=0$ e Im$(z) \neq 0$
### Operações na forma algébrica
- $(a + bi) + (c + di) = a + c + (b + d)i$
	>[!Note] Exemplo
	>$(2, -3) + (5, 6) =$
	>$= 2 - 3i + 5 + 6i =$
	>$= 2+5 + (-3+6)i=$
	>$=7 + 3i$

- $(a + bi) \times (c + di) = (ac - bd) + (ad + bc)i$
  >[!Note] Exemplo
  >$(3, 5) \times 2, 4=$
  >$=(3+5i) \times (2+4i)=$
  >$=(3 \times 2 - 5 \times 4) + (3 \times 4 + 5 \times 2)i=$
  >$=-14 + 22i$
  
### Plano complexo / Plano de Argand