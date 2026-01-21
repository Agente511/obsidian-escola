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
Dada uma função real de variável real $f$, contínua num intervalo $I=[a,\ b]$, com $a < b$, para qualquer valor $k \in \mathbb R$ do intervalo de extremos $f(a)$ e $f(b)$ existe $c \in I$ tal que $f(c)=k$, ou seja:

 Se
 - $f$ é contínua em $[a,\ b]$
 - $f(a) < k f(b)$ ou $