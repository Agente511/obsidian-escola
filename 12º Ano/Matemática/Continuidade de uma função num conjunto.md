## Continuidade num conjunto
Sejam $f$ um função de variável real de domínio $D_f$ e $A \subset D_f$. Diz-se que:
- $f$ é **contínua no conjunto $A$** quando é **contínua em todos os pontos de $A$**.
- $f$ é **contínua** quando é **contínua em todos os pontos de $D_f$**.
### Propriedades
*(Igual ao que estava em [[Continuidade de uma função num ponto#Teoremas sobre continuidade]])*:

- Sejam $f$ e $g$ funções reais de variável real e contínuas num ponto $a$. Então, também são contínuas em $a$:
	- $f+g$
	- $f-g$
	- $f \times g$
	- $\frac f g$, $g\neq 0$
	- $f^n$, $n \in \mathbb N$
	- $\sqrt[n] f$, $n$ par
- Se **$f$ é contínua em $a$** e **$g$ é contínua em $f(a)$** então a [[Funções#Composição de Funções|função composta]] **$g \circ f$ é contínua em $a$**.
- Se **$\underset{x \rightarrow a} \lim f(x) = 0$** e **$g$ é limitada** então **$\underset{x \rightarrow a} \lim f(x) \times g(x)=0$**.
- As **funções trigonométricas $\sin x$ e $\cos x$ são contínuas**.

## Teorema de Bolzano-Cauchy (Teorema dos valores intermédios)
Dada uma função real de variável real $f$, contínua num intervalo $I=[a,\ b]$, com $a < b$, então para qualquer valor $k \in \mathbb R$ do intervalo de extremos $f(a)$ e $f(b)$ existe $c \in I$ tal que $f(c)=k$, ou seja:

> [!Summary] Teorema de Bolzano-Cauchy
>  Se
>  - $f$ é contínua em $[a,\ b]$
>  - $f(a) < k < f(b)$ ou $f(b) < k < f(a)$
> 
> Então:
> - $\exists\ c \in ]a,\ b[: f(c)=k$ 

>[!Summary] Método para resolver problemas aplicando o Teorema de Bolzano-Cauchy
>1. **Provar** que a **função é contínua** no **intervalo considerado**.
>2. Calcular **imagens dos extremos do intervalo**.
>3. **Enquadrar a imagem considerada entre as imagens dos extremos do intervalo**.
>4. Escrever as **conclusões**.
>
>>[!Note] Exemplo
>>>Considera a função $f(x)=-x^3+2x^2-5$. Prova que a equação $f(x)=-\pi$ tem, pelo menos, uma solução no intervalo $]-1,1[$.
>>
>>1. A função $f$ é uma função polinomial, contínua em $\mathbb R$, logo contínua em $[-1,\ 1] \subset \mathbb R$.
>>2. $f(-1)=-(-1)^3+2(-1)^2-5=1+2-5=-2$
>>   $f(1)=-1^3+2 \times 1^2-5=-1+2-5=4$
>>3. Tem-se que $f(-1)>-\pi>f(1)$.
>>4. Assim, pelo Teorema de Bolzano-Cauchy, podemos concluir que existe pelo menos uma solução da equação $f(x)=-\pi$ no intervalo $]-1,1[$.

### Corolário do Teorema de Bolzano-Cauchy
Caso particular que permite justificar a **existência de zeros de funções contínuas**.
> [!Summary] Corolário do Teorema de Bolzano-Cauchy
>  Se
>  - $f$ é contínua em $[a,\ b]$
>  - $f(a) \times f(b)< 0$
> 
> Então:
> - $\exists\ c \in ]a,\ b[: f(c)=0$ 

