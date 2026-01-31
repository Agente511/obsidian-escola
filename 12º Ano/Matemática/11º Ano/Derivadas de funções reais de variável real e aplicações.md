## Taxa média de variação
A taxa média de variação traduz a **variação média de $f$ por cada unidade de variação da variável independente**.

>[!Summary]  Taxa média de variação de $f$ entre $a$ e $b$
>Dada uma função real de variável real $f$ e dois pontos distintos, $a$ e $b$, do seu domínio:
>
>$\large t.m.v._{[a,\ b]} = \frac {f(b)-f(a)} {b-a} = m_s = \tan \alpha$
>![[images.png]]

Geometricamente, a taxa média de variação de $f$ entre $a$ e $b$ é o **declive da reta que passa nos pontos do gráfico de $f$ de abcissas $a$ e $b$**.

>[!Info] Nota
>Quando a função estabelece uma **correspondência entre tempo e distância percorrida**, a taxa média de variação chama-se **[[Segunda derivada, aplicações e problemas de otimização#Noção de derivada aplicada à cinemática do ponto|velocidade média]]**.
### Relação com a monotonia da função
- Se uma função é **estritamente crescente** (ou, respetivamente, **estritamente decrescente**) num conjunto $D$ do seu domínio, então, para quaisquer $a$ e $b$ pertencentes a $D$, a **taxa média de variação** de $f$ entre $a$ e $b$ é **positiva** (respetivamente, **negativa**).
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
Geometricamente, **$f'(a)$ é o declive da reta tangente ao gráfico de $f$ no ponto $a$**.

>[!Summary] Equação da reta tangente ao gráfico de $f$ no ponto de abcissa $a$
>$\large y = f'(a) (x-a) + f(a)$

## Função derivada
Dada uma função real de variável real $f$, designa-se por função derivada de $f$ a função de domínio $D_f = \{x \in D_f: f$ é diferenciável em $x\}$.
Representa-se por $f'$.

> [!Summary] Teorema
> Dada uma função de variável real $f$ e um ponto $a \in D_f$, se $f$ é diferenciável em $a$, então **$f$ é contínua em $a$**.
> >[!Warning] A implicação recíproca não é necessariamente verdadeira.
> >$f$ pode ser contínua em $x=a$ e não ser diferenciável em $x=a$.
### Regras da derivação
Considerando:
\- $f$ e $g$ funções reais de variável real de domínio $D$
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
	$(x^n)'=n\ n'\ x^{n-1} = n\ x^{n-1}$
	>[!Note] Exemplos
	>- $(x^2)'=2\ x$
	>- $(x^3)'=3\ x^{2}$
	>- $(\frac 1 x)'=(x^{-1})'=-x^{-2}=-\frac 1 {x^2}$
	>- $(\sqrt x)'= (x^{\frac 1 2})' = \frac 1 2 \times x^{-\frac 1 2}= \frac 1 2 \times \frac 1 {x^2}= \frac 1 {2 \sqrt x}$
	>- $(f^n)'= n\ f'\ f^{n-1}$

- ##### Produto
	$(f \times g)'= f' \times g + g' \times f$
- ##### Quociente
	$(\frac f g)'=$ $\large \frac {f' \times g - g' \times f} {g^2}$, $g \neq 0$
- ##### [[Funções#Composição de Funções|Função composta]]
	$(g \circ f)'(a)= f'(a) \times g'(f(a))$
## Aplicação da noção de derivada ao estudo de funções
>[!Summary] Teoremas
>Seja $f$ uma função real de variável real $f$, contínua num intervalo $I$ de extremo esquerdo $a$ e extremo direito $b$ e diferenciável em $]a, b[$.
>- Se $\forall x \in ]a,b[,\ f'(x) > 0$, então $f$ é **crescente em $I$**.
>- Se $\forall x \in ]a,b[,\ f'(x) \geq 0$, então $f$ é **crescente em sentido lato em $I$**.
>- Se $\forall x \in ]a, b[,\ f('x) = 0$, então $f$ é **constante em $I$**.
>- Se $\forall x \in ]a, b[,\ f('x) < 0$, então $f$ é **decrescente em $I$**.
>- Se $\forall x \in ]a, b[,\ f('x) \leq 0$, então $f$ é **decrescente em sentido lato em $I$**.

^19c1a2

### Primeira derivada aplicada ao estudo dos intervalos de monotonia e da existência de extremos relativos
>[!Summary] Método para estudar os intervalos de monotonia e a existência de extremos relativos de uma função diferenciável $f$
>1. Determinar o **domínio** da função $f$.
>2. Calcular a **1.ª derivada** ($f'(x)$).
>3. Determinar os **zeros da derivada**, através da equação **$f'(x)=0$**.
>4. Construir um quadro que relacione o **sinal de f' e os zeros da 1.ª derivada** com a **monotonia e os extremos relativos da função**.
>	> [!NOTE] Exemplo
>	> | $x$     | $-\infty$  | $\frac 1 3$        |            | $1$                | $+\infty$  |
>	> | ------- | ---------- | ------------------ | ---------- | ------------------ | ---------- |
>	> | $f'(x)$ | $+$        | $0$                | $-$        | $0$                | $+$        |
>	> | $f(x)$  | $\nearrow$ | Máximo<br>relativo | $\searrow$ | Mínimo<br>relativo | $\nearrow$ |
>
>5. Escrever as **conclusões**.
> 	>[!Note] Exemplo
> 	>A função $f$ é crescente em $]-\infty, \frac \ 3$ e em $]1, +\infty[$ e decrescente em $]\frac 1 3, 1[$.
> 	>
> 	>Existe um máximo relativo em $x=\frac 1 3$ de valor $f(\frac 1 3)$ e um mínimo relativo em $x=1$ de valor $f(1)$..
