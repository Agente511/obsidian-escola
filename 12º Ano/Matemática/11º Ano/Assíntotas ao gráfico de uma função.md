## Assíntotas verticais
Dados um referencial cartesiano, uma função real de variável real $f$ e um número real $a$, diz-se que a **reta de equação $x=a$** é **assíntota vertical ao gráfico de $f$** se e só se **pelo menos um dos [[Limite segundo Heine#Limites laterais|limites laterais]] de $f(x)$ no ponto $a$ for infinito** ($-\infty$ ou $+\infty$).

### Existência de assíntotas verticais
>[!Summary] Passos para investigar a existência de assíntotas verticais ao gráfico de $f$
>1. Determinar o **domínio de $f$**.
>   Identificar os **pontos $a$** que **não pertencem ao domínio** ou em que a **função pode ser descontínua**.
>2. Calcular, para os valores de $a$ identificados, **$\underset{x \rightarrow a^-} \lim f(x)$ e $\underset{x \rightarrow a^+} \lim f(x)$**.
>3. Se **$\underset{x \rightarrow a^{(+ ou -)}} \lim f(x) =(+ \text{ ou } -)\infty$**, conclui-se que **$x=a$ é uma assíntota vertical ao gráfico da função $f$**.

## Assíntotas não verticais
Dados um referencial cartesiano e uma função real de variável real $f$ de domínio $D_f$, não majorado (e, respetivamente, não minorado), diz-se que a reta de equação **$y=mx+b$ é assíntota ao gráfico de $f$ em $+\infty$ (e em $-\infty$)**, se e só se **$\underset{x \rightarrow +\infty} \lim [f(x)-(mx+b)]=0$ (e $\underset{x \rightarrow -\infty} \lim [f(x)-(mx+b)]=0$)**.

- Quando **$m=0$**, é uma **assíntota horizontal**
- Quando $m \neq 0$, é uma **assíntota oblíqua**.

>[!Summary] Passos para investigar a existência de assíntotas não verticais ao gráfico de $f$
>1. Calcular $m$:
>   **$$\begin{flalign}& m=\underset{x \rightarrow (+ \text{ ou } - \infty)} \lim \frac {f(x)} x = k_1 \in \mathbb R &\end{flalign}$$**
>2. Calcular $b$:
>   **$$\begin{flalign}& b=\underset{x \rightarrow (+ \text{ ou } - \infty)} \lim [f(x)-mx] = k_2 \in \mathbb R &\end{flalign}$$**
>3. Conclui-se que **y=mx+b é assíntota não vertical ao gráfico de $f$**.
