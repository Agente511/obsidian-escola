Função em que a cada número real associa o seu módulo.

>[!Summary] Forma geral
>- **Vértice:** $V(h,k)$
>- **Equação do eixo de simetria:** $x=h$
>- **Abertura:**
>	- Se $a>0$, a abertura do gráfico é voltada para **cima**
>	- Se $a<0$, a abertura do gráfico é voltada para **baixo**

>[!Note] Exemplo
>$f: \mathbb R \rightarrow \mathbb R$
>tal que $f(x)=|x|$
>![[Pasted image 20240601124723.png]]
>- $D_f=\mathbb R$
>- $D'_f=\mathbb R^+_0$
>- **Zeros da função:** 0
>- **Sinal:** positivo em $\mathbb R$
>- **Monotonia:** decrescente em $]-\infty;0]$ e crescente em $[0;+\infty]$
>- **Vértice:** $V(0,0)$
>- **Eixo de simetria:** $x=0$
>- **Injetividade:** não é injetiva
>- **Paridade:** é uma função par

>[!Tip] **Nota**
>O **$x$ do vértice** também pode ser determinado através do **cálculo do ponto médio dos zeros**.
## Determinação do $x$
---
>[!Summary] Forma geral
>Funções do tipo $f(x)=a|x-h|+k$ com $a,h,k \in \mathbb R$ e $a \neq 0$.
>
>Seja $a \in \mathbb R$
>- Se $a>0 \iff |x|=a \iff x=a \lor x =-a$
>- Se $a=0 \iff |x|=0 \iff x=0$
>- Se $a<0$, a equação é impossível
>>[!Note] Exemplo
>>- $f(x)=2 \iff |x|=2 \iff x=2 \lor x=-2$
>> CS: {$-2;2$}
>>
>>- $f(x)=0 \iff |x|=0 \iff x=0$
>>  CS: {$0$}
>>
>>- $f(x)=-4 \iff |x|=-4$
>>  Equação impossível CS: { }

>[!Note] Mais exemplos
>- $|x-5|=4 \iff x-5=4 \lor x-5 =-4 \iff x=9 \lor x=1$
>  CS: {$1;9$}
>- $|2x|=8 \iff 2x=-8 \lor 2x=8 \iff x=-4 \lor x=4$
>  CS: {$-4;4$}
>- $4|3x-2|-5=15 \iff 4|3x-2|=20 \iff |3x-2|=5 \iff 3x-2=-5 \lor 3x-2=5 \iff 3x=-3 \lor 3x=7 \iff x=-1 \lor x=\frac 7 3$
>  CS: {$-1;\frac 7 3$}
>

## Inequações com módulos
---
>[!Summary] Forma geral
>Seja $a \in \mathbb R, |x|<a$
>- Se $a \leq 0$, a inequação é impossível
>- Se $a>0$, $|x|<a \iff x<a \land x>-a$
>
>Seja $a \in \mathbb R, |x| >a$
>- Se $a < 0$, condição universal CS:$\mathbb R$
>- Se $a=0, |x|>0 \iff x \in \mathbb R$ \\{$0$}
>- Se $a>0$, $|x|>a \iff x>a \land x<-a$

>[!Note] Exemplo
>$|x|<2$
>$\iff x<2 \land x>-2$
>CS: $]-2;2[$
>![[Pasted image 20240601144549.png]]

>[!Note] Mais exemplos
>- $|x-2|<3 \iff x-2>-3 \land x-2<3 \iff x>-1 \land x<5$
>  CS: $]-1;5[$
>- $|2x+5|-4<5 \iff |2x+5|<9 \iff 2x+5 > -9 \land 2x+5 <9 \iff 2x>-14 \land 2x<4 \iff x>-\frac {14} 2 \land x<\frac 4 2$
>  CS:$]-7;2[

## Inequações com módulos definidas por ramos
---
$f(x) = |x| = \begin{cases} x & \text{se } x\geq 0 \\-x & \text{se } x<0 \end{cases}$

>[!Note] Exemplos
>- $f(x) = |x+2| = \begin{cases} x+2 & \text{se } x+2\geq 0 \\-x-2 & \text{se } x+2<0 \end{cases} \iff \begin{cases} x+2 & \text{se } x\geq -2 \\-x-2 & \text{se } x<-2 \end{cases}$
>- $f(x) = |2x+1| = \begin{cases} 2x+1 & \text{se } x\geq -\frac 1 2 \\-2x-1 & \text{se } x< - \frac 1 2 \end{cases}$
