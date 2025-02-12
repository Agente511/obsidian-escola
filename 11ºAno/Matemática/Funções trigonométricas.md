## Período
Dado um número $p>0$ e uma função $f$, dizemos que $f$ é **periódica de período de p** ou periódica se
$\forall x\in D_f$ ,   $(x+p)\in D_f$    e    $f(x+p)=f(x)$

Se $f$ é **periódica de período p** ($p>0$) então também é **periódica de período kp**, $k\in \mathbb Z$.
### Período positivo mínimo (ou período fundamental)
p é o **período positivo mínimo** ou **período fundamental** se **p for o menor nº positivo que é período de $f$**.

>[!Note] Exemplo
>- $\sin(x+2\pi)=\sin(x)$
>- $\sin(x+6\pi)=\sin(x)$
>
>$2\pi$ é o período positivo mínimo de $\sin(x)$.

## Função seno
$f(x)=\sin(x)$
![[Pasted image 20241128001901.png|400]]
- $D_f=\mathbb R$
- $D'f=[-1,1]$

Interação com os eixos:
- int. $Oy \rightarrow f(0)=0$
- int. $Ox$: zeros:
        $\ \ \ \ \ \ \ \ \ \ \sin(x)=0$
        $\iff x=k\pi, k\in \mathbb Z$
### Extremos
- Máximo: $1$ em $x=\frac \pi 2+2k\pi, k\in \mathbb Z$
- Mínimo: $-1$ em $x=-\frac \pi 2+2k\pi, k\in \mathbb Z$
### Monotonia
- Crescente: $[- \frac \pi 2+ 2k\pi, \frac \pi 2+2k\pi], k\in \mathbb Z$
- Decrescente: $[\frac \pi 2+ 2k\pi, \frac {3\pi} 2+2k\pi], k\in \mathbb Z$
### Paridade
$\forall x \in \mathbb R,\ sin(-x)=-\sin(x), f$ é **[[Funções pares e ímpares#Funções ímpares|ímpar]]**.
Logo, o **gráfico é simétrico em relação à origem**.
### Período
Período positivo mínimo é $2\pi$.
$\sin(2\pi+x)=\sin(x)$
>[!Note] Exemplos
>$f(x)=1+\sin(x)$
>  $D_f=\mathbb R$
>  $D'_f=[0,2]$
>  
>  $$\begin{flalign}& \ \ \ \ \ \ \ \ \ \ -1\leq \sin(x) \leq 1 &\end{flalign}$$
>  $$\begin{flalign}& \iff -1+1 \leq \sin(x)+1 \leq 1+1 &\end{flalign}$$
>  $$\begin{flalign}& \iff 0 \leq \sin(x)+1 \leq 2 &\end{flalign}$$
>  
>  Zeros
>  $$\begin{flalign}&\ \ \ \ \ \ \ \ \ \ f(x)=0  &\end{flalign}$$
>  $$\begin{flalign}&\iff 1+\sin(x)=0  &\end{flalign}$$
>  $$\begin{flalign}& \sin(x)=-1 &\end{flalign}$$
>  $$\begin{flalign}& x=\frac {3\pi} 2 +2k\pi, k\in \mathbb Z &\end{flalign}$$

## Função cosseno
$g(x)=\cos(x)$
![[Pasted image 20241128001930.png|400]]
- $D_g=\mathbb R$
- $D'g=[-1,1]$

Interação com os eixos:
- int. $Oy \rightarrow g(0)=1$
- int. $Ox$: zeros:
        $\ \ \ \ \ \ \ \ \ \ \cos(x)=0$
        $\iff x=\frac \pi 2 +k\pi, k\in \mathbb Z$
### Extremos
- Máximo: $1$ em $x=2k\pi, k\in \mathbb Z$
- Mínimo: $-1$ em $x=\pi+2k\pi, k\in \mathbb Z$
### Monotonia
- Crescente: $[\pi+2k\pi, 2\pi +2k\pi], k\in \mathbb Z$
- Decrescente: $[2k\pi, \pi+2k\pi], k\in \mathbb Z$
### Paridade
$\forall x \in \mathbb R,\ cos(-x)=\cos(x), g$ é **[[Funções pares e ímpares#Funções pares|par]]**.
Logo, o **gráfico é simétrico em relação a $Oy$**.
### Período
Período positivo mínimo é $2\pi$.
$\cos(2\pi+x)=\cos(x)$
>[!Note] Exemplos
>$f(x)=\cos(x)$
>  $D_f=[-\frac \pi 2, \frac {2\pi} 3]$
>Determina o contradomínio de $f$ 
>  
>  $$\begin{flalign}& \ \ \ \ \ \ \ \ \ \ f(-\frac \pi 2)=\cos(-\frac \pi 2)=0 &\end{flalign}$$
>  $$\begin{flalign}& f(\frac {2\pi} 3)=\cos (\frac {2\pi} 3)=\cos (\pi-\frac \pi 3)=-\cos (\frac \pi 3)=-\frac 1 2 &\end{flalign}$$
>  
>  R.: $D'_f=[-\frac 1 2, 1]$

## Função tangente
$h(x)=\tan(x)$
![[Pasted image 20241128002031.png|400]]
- $D_h=\mathbb R$ \ $\{\frac \pi 2 +k\pi, k\in \mathbb Z \}$
- $D'h=\mathbb R$

Interação com os eixos:
- int. $Oy \rightarrow h(0)=0$
- int. $Ox$: zeros:
        $\ \ \ \ \ \ \ \ \ \ \tan(x)=0$
        $\iff x=k\pi, k\in \mathbb Z$
### Extremos
Não tem.
### Monotonia
como não há extremos não dá.
### Paridade
$\tan(-x)=-\tan(x), \forall x\in D_h,\ h$ é **[[Funções pares e ímpares#Funções ímpares|ímpar]]**.
Logo, o **gráfico é simétrico em relação à origem**.
### Período
Período positivo mínimo é $\pi$.
$\tan(x+\pi)=\tan(x)$


