## Juros compostos
Dado um capital inicial $C_0$, e aplicando-se **juros compostos à taxa de $r\%$ a $T$**, tem-se que o capital disponível, ao fim de $n$ períodos de tempo $T$, é igual:

$\large C_n= C_0(1 + \frac r {100})^n$

Sejam $r \in \mathbb R$, $n \in \mathbb N$ e $C_0$ um capital disponível no início de um determinado período de um ano. Se **dividirmos esse ano em $n$ períodos iguais**, de medida temporal $T$, e aplicarmos **juros compostos à taxa de $\frac r n \%$ a $T$**, durante esses $n$ períodos ao capital inicial $C_0$, o capital disponível ao fim de um ano é igual a:

$\large C_n= C_0(1 + \frac r {100n})^n$
## Número de Neper
>[!Summary] Teorema
>A sucessão de termo geral $\large U_n=(1 + \frac 1 n)^n$ é
>-  **Crescente** ($u_{n+1}-u_n>0$).
>- **Limitada**
>- Monótona e limitada, logo **convergente**.

Assim, o limite de $\lim(1+\frac 1 n)^n$ é um número irracional, designado por **número de Neper** ou número de Euler, geralmente representado por $e$.
- $\large \lim(1+\frac 1 n)^n=e$
- $\large e \approx 2,71828...$
## Funções exponenciais
Designa-se por função exponencial a função $f(x)=a^x$, com **$a \in \mathbb R$ tal que $a>0$**, sendo uma expressão em que a **base é constante** e o **expoente é variável**.
### Propriedades
- **Sinal**: $f(x)>0$
- $\underset{x\to 0} \lim  f(x) = \underset{x\to 0} \lim a^0 = 1$
- É **contínua**
- **Domínio**: $D=\mathbb R$
- **Contradomínio**: $D' = ]0;+\infty[ = \mathbb R^+$
- **Zeros**: não tem zeros
- **Assíntotas**: $y=0$ é assíntota vertical ao gráfico da função

- > [!Summary] Propriedades das funções exponencias de base $a>1$
> ![[Pasted image 20260314164900.png]]
> - **Monotonia**: monótona crescente
> - $\underset{x\to +\infty} \lim f(x)=+\infty$
> - $\underset{x\to -\infty} \lim f(x)=0$

- > [!Summary] Propriedades das funções exponencias de base $0<a<1$
> ![[Pasted image 20260314165035.png]]
> - **Monotonia**: monótona decrescente
> -  $\underset{x\to +\infty} \lim f(x)=0$
> - $\underset{x\to -\infty} \lim f(x)=+\infty$

#### Propriedades algébricas de potências
Sejam $a, b \in \mathbb R ^+$ e $x, y \in \mathbb R$ tem-se que:
- $a^x \times a^y = a^{x+y}$
- $(a^x)^y= a^{x \times y}$
- $\frac 1 {a^x} = a^{-x}$
- $\frac {a^x} {a^y} = a^{x-y}$
- $(ab)^x = a^x \times b^x$
- $(\frac a b)^x = \frac {a^x} {b^x}$ 
### Equações exponenciais
Seja $a \in \mathbb R^+$ e $x,y \in \mathbb R$:
$\large a^x = a^y \iff x = y$

>[!Example] Resolução de equações exponenciais
>1. Sempre que possível, escrever as potências na mesma base, aplicando as regras operatórias das potências.
>2. Obter uma igualdade do tipo $a^x=a^y$.
>3. Aplicar $a^x = a^y \iff x = y$.
>4. Resolver a equação obtida.
>5. Apresentar o conjunto-solução.
### Inequações
### Limite
### Limite notável
### Derivada da função exponencial