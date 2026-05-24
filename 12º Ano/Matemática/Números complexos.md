## Números complexos
O conjunto $\mathbb C$ é uma extensão de $\mathbb R$ que contém as raízes pares de números negativos.
### Operações
Designa-se por **corpo dos números complexos**, e representa-se por $\mathbb C$, o conjunto $\mathbb R^2$ munido das seguintes operações:
- $(a, b) \pm (c, d) = (a \pm c, b \pm d)$
- $(a, b) \times (c, d) = (ac - bd, ad + bc)$

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
Dado um plano munido de um referencial ortonormado direto e dados $a$, $b$ $in \mathbb R$, designa-se por **afixo do número complexo $z=a + bi$** o **ponto M de coordenadas $(a, b)$**.
![[Pasted image 20260523180756.png|260]]

O eixo das **abcissas** designa-se por **eixo real**.
O eixo das **ordenadas** designa-se por **eixo imaginário**.
#### Adição de números complexos no plano complexo
Dados dois números complexos $z= x + yi$ e $z_0=a+bi$, com $x$, $y$, $a$, $b$ $\in \mathbb R$, o **afixo de $z+z_0$** é a imagem pela translação de vetor $\vec u(a, b)$ do ponto $M$, afixo de $z$:
![[Pasted image 20260523181050.png|260]]

### Simétrico de um número complexo
$\large -z= - (a+bi) = -a-bi$

$(-z)+z=0$

Dois números complexos simétricos têm **partes reais simétricas** e **partes imaginárias simétricas**.

O ponto afixo de $-z$, $M'(-a, -b)$, é a imagem da reflexão central de centro $O$ de $M(a, b)$ ponto afixo de $z$.
![[Pasted image 20260523181337.png|260]]

### Conjugado de um número complexo
$\large \overline z = \overline {(a+bi)} = a-bi$

Dois números complexos conjugados têm **partes reais iguais** e **partes imaginárias simétricas**.

O ponto afixo de $\overline z$, $M'(a, -b)$, é a imagem pela reflexão de eixo real de $M(a, b$), ponto afixo de $z$.
![[Pasted image 20260523181830.png|260]]

>[!Summary] Propriedades relativas ao conjugado de números complexos
>- $\overline {\overline z} = z$
>- $\overline {z+w} = \overline z + \overline w$
>- $\overline {zw} = \overline z \times \overline w$
>- Re$(z) = \large \frac {z + \overline z} 2$
>- Im$(z) = \large \frac {z + \overline z} {2i}$
>- $z$ é um número **real** se e só se $z = \overline z \land z \neq 0$
>- $z$ é um número **imaginário puro** se e só se $z = -\overline z \land z \neq 0$

### Módulo de um número complexo
Designa-se por módulo de $z$ a **medida da distância**, no plano complexo, **entre a origem e o ponto afixo de $z$** e representa-se por $|z|$.

![[Pasted image 20260523180756.png|260]]

$\large |z| = \sqrt {a^2 + b^2}$

>[!Summary] Propriedades relativas ao módulo de um número complexo
>Sejam $z$ e $w$ dois números complexos tem-se que:
>- $\large |z| = 0 \iff z = 0$
>- $\large |zw| = |z| |w|$
>- $\large |z| = |\overline z|$
>- $\large |z+w| \leq |z| + |w|$
>- $\large |z|^2 = z |z|$
>- $\large | \frac w z | = \frac {|w|} {|z|}$
>- $\large \overline {(\frac w z)} = \frac {\overline w} {\overline z}$

### Inverso de um número complexo não nulo
$\large \frac 1 z = \frac {1} {|z|^2} \overline z$

### Divisão de números complexos
Dados dois números complexos $w$ e $z$, $z \neq 0$, tem-se que o quociente de $w$ por $z$ é:
$\large \frac w z = w \times \frac 1 z$

Para determinar o quociente de $w$ por $z$, basta determinar o quociente de $w\overline z$ por $z \overline z$:
$\large \frac w z = w \times \frac 1 z = w \frac 1 {|z|^2} \times \overline z = \frac {w \overline z} {z \overline z}$

No caso particular de $z$ ser um imaginário puro, basta multiplicar $w$ e $z$ por $i$:
>[!Note] Exemplo
>$\frac {1 + 2i} {3i} = \frac {(1+2i)i} {3i^2} = \frac {i - 2} {-3} = \frac 2 3 - \frac 1 3 i$

### Potenciação de números complexos
Seja $n \in \mathbb N_0$, tem-se que:
$\large i^n = i^r$, sendo $r$ o resto da divisão inteira de $n$ por 4

>[!Note] Exemplo
>$i^{407}=i^{4\times 101 + 3}= i^3 = -i$
#### Potências de expoente inteiro de um número complexo
De forma análoga ao que se passa em $\mathbb R$, para $n \in \mathbb N$, tem-se que:
- $\large (a+bi)^n=(a+bi) \times ... \times (a+bi)$
- $\large (a+bi)^{-n}=\frac 1 {(a+bi)^n}=\frac 1 {(a+bi) \times ... \times (a+bi)}$, $\ \ a+bi \neq 0$ 

