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
- **Domínio**: $D=\mathbb R$
- **Contradomínio**: $D' = ]0;+\infty[ = \mathbb R^+$
- **Zeros**: não tem zeros
- **Sinal**: $f(x)>0$
- $\underset{x\to 0} \lim  f(x) = \underset{x\to 0} \lim a^0 = 1$
- **Contínua**
- **Assíntotas**: $y=0$ é assíntota vertical ao gráfico da função

- > [!Summary] Propriedades das funções exponencias de base $a>1$
> ![[Pasted image 20260314164900.png]]
> - **Monotonia**: estritamente crescente
> - $\underset{x\to +\infty} \lim f(x)=+\infty$
> - $\underset{x\to -\infty} \lim f(x)=0$
 >
 >^46bf1d
- > [!Summary] Propriedades das funções exponencias de base $0<a<1$
> ![[Pasted image 20260314165035.png]]
> - **Monotonia**: estritamente decrescente
> -  $\underset{x\to +\infty} \lim f(x)=0$
> - $\underset{x\to -\infty} \lim f(x)=+\infty$
> 
> ^a359aa

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

>[!Note] Exemplos
>1. $2^{x+1} = 8$
>>$\iff 2^{x+1} = 2^3$
>>$\iff x+1 = 3$
>>$\iff x=2$
>>$S=\{2\}$
>
>2. $4^x-2^x-2=0$
>>$\iff (2^x)^2-2^x-2=0$
>>Mudança de variável $y=2^x$
>>$\iff y^2-y-2=0$
>>$\iff y=\frac {1 \pm \sqrt{1^2-4\times 1 \times (-2)}} {2 \times 1}$
>>$\iff y = \frac {1 \pm \sqrt 9} 2$
>>$\iff y = -1 \lor y=2$
>>M.V.
>>$\iff \cancel{2^x=-1} \tiny \text{impossível} \normalsize \lor 2^x=2^1$
>>$\iff x=1$
>>$S=\{1\}$
### Inequações exponenciais
Seja $a \in \mathbb R^+$ e $x,y \in \mathbb R$:
- Se **$a>1$**, a função é **[[#^46bf1d|estritamente crescente]]**, logo $\large a^x < a^y \iff x < y$ (**sinal mantém-se**)
- Se **$0<a<1$**, a função é **[[#^a359aa|estritamente decrescente]]**, logo $\large a^x < a^y \iff x > y$ (**sinal inverte**)

>[!Example] Resolução de inequações exponenciais
>1. Sempre que possível, escrever as potências na mesma base, aplicando as regras operatórias das potências.
>2. Obter uma desigualdade do tipo $a^x<a^y$ ou $a^x \leq a^y$ ou $a^x>a^y$ ou $a^x \geq a^y$.
>3. Se $a>1$, mantém-se o sinal.
>   Se $0<a<1$, inverte-se o sinal.
>4. Resolver a inequação obtida.
>5. Apresentar o conjunto-solução.

>[!Note] Exemplos
>1. $2^x-4 \geq 0$
>>$\iff 2^x \geq 4$
>>$\iff 2^x \geq 2^2$
>>$\iff x \geq 2$
>>$S=[2, +\infty[$
>
>2. $(\frac 1 2)^2 - \frac 1 2 < 0$
>>$\iff (\frac 1 2) ^x < \frac 1 2$
>>$\iff x>1$
>>$S=]1, +\infty[$
### Limite $\lim (1 +\frac x n)^n=e^x$
>[!Summary] Teorema
>$\large \lim (1+\frac x n)^n=e^x$

>[!Summary] Teorema
>Seja $f$ a função definida em $\mathbb R$ \ $[-1,0]$, por $f(y)=(1+\frac 1 y)^y$. Tem-se que:
>
>$\large \underset{y \to \pm \infty} \lim (1+\frac 1 y)^y=e$
### Limite notável $\underset{h\to 0} \lim \frac {e^h-1} h = 1$ 
$\large \underset{h\to 0} \lim \frac {e^h-1} h = 1$
### Derivada da função exponencial de base $e$
Seja $f(x)=e^x$, com $x \in \mathbb R$, conclui-se que $f'(x)=e^x$, isto é:
$\large (e^x)'=e^x$

Pelo teorema da derivada da função composta, tem-se que:
$\large (e^u)'=u'e^u$

>[!Note] Exemplos
>1. $(e^{\cos x})'=(\cos x)' \times e^{\cos x}=-\sin x \times e^{\cos x}$
>2. $(\frac {e^x-1} {e^x})'=$
>	$= \frac {(e^x-1)' \times e^x - (e^x)' \times (e^x-1)} {(e^x)^2}=$
>	$=\frac {e^x \times e^x - e^x \times (e^x-1)} {(e^x)^2}=$
>	$=\frac {e^x(e^x-e^x-1)} {(e^x)^2}=$
>	$= \frac 1 {e^x}$