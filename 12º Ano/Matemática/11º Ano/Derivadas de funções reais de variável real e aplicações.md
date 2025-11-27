*(feito à pressa, então possivelmente inacabado/impreciso)*
## Taxa média de variação
A taxa média de variação traduz a **variação média de $f$ por cauda unidade de variação da variável independente**.

>[!Summary]  Taxa média de variação de $f$ entre $a$ e $b$
>Dada uma função real de variável real $f$ e dois pontos distintos, $a$ e $b$, do seu domínio:
>
>$\large t.m.v._{[a,\ b]} = \frac {f(b)-f(a)} {b-a} = m_s = \tan \alpha$
>![[images.png]]

Geometricamente, a taxa média de variação de $f$ entre $a$ e $b$ é o **declive da reta que passa nos pontos do gráfico de $f$ de abcissas $a$ e $b$**.

>[!Tip] Nota
>Quando a função estabelece uma **correspondência entre tempo e distância percorrida**, a taxa média de variação chama-se **velocidade média**.
### Relação com a monotonia da função
- Se uma função é **estritamente crescente** (ou, respetivamente, **decrescente**) num conjunto $D$ do seu domínio, então, para quaisquer $a$ e $b$ pertencentes a $D$, a **taxa média de variação** de $f$ entre $a$ e $b$ é **positiva** (respetivamente, **negativa**).
- Se uma função é **constante** num conjunto $D$ do seu domínio, então, para quaisquer $a$ e $b$ pertencentes a $D$, a **taxa média de variação** de $f$ entre $a$ e $b$ é **zero**.
  >[!Warning] As implicações recíprocas destas são falsas.

## Definição de derivada
A **taxa instantânea de variação** de $f$ no ponto $a$, designa-se por **derivada de $f$ no ponto $a$**.

> [!Summary] Definição de derivada de $f$ no ponto $a$
>Dada uma função real de variável real $f$ e um ponto $a$ do seu domínio:
>
>$\large f'(a) = \underset{x \rightarrow a} \lim \frac {f(x)-f(a)} {x-a}$

Quando existe derivada de $f$ em $a$, diz-se que **$f$ é diferenciável** (ou derivável) **em $a$**.
Uma função é **diferenciável** se for **diferenciável no domínio**.

### Reta tangente ao gráfico de $f$ no ponto $a$
Geometricamente, $f'(a)$ é o declive da reta tangente ao gráfico de $f$ no ponto $a$.

>[!Summary] Equação da reta tangente ao gráfico de $f$ no ponto de abcissa $a$
>$\large y = f'(a) (x-a) + f(a)$

## Função derivada
Dada uma função real de variável real $f$, designa-se por função derivada de $f$ a função de domínio $D_f = \{x \in D_f: f$ é diferenciável em $x\}$.
Representa-se por $f'$.

> [!Summary] Teorema
> Dada uma função de variável real $f$ e um ponto $a \in D_f$, se $f$ é diferenciável em $a$, então **$f$ é contínua em $a$**.
> >[!Warning] A implicação recíproca não é necessariamente verdadeira.
> >$f$ pode ser contínua em $a$ e não ser diferenciável em $x$.

### Regras da derivação
Considerando:
\- $f$ e $g$ funções reais de variável real de domínio D
\- $a \in D$
\- $k \in \mathbb R$
\- $f$ e $g$ diferenciáveis em $a$

- ##### Soma e diferença
  $(f+g)'=f' + g'$
- ##### Produto por uma constante
  $(k\ f)'=k\ f', k \in \mathbb R$
- ##### Constante
	$k'=0$
- ##### $x$
	$x'=1$
- ##### Potência
	$(x^n)'=n\ x^{n-1}$
	>[!Note] Exemplos
	>- $(x^2)'=2\ x$
	>- $(x^3)'=3\ x^{2}$
	>- $(x^4)'=4\ x^{3}$

- ##### Produto
	