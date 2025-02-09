## Vetores e planos
### Vetor normal a um plano
Um vetor $\vec v$ é **normal ao plano $\alpha$**, se $\vec v$ for nulo ou se as **retas do vetor diretor $\vec v$ forem perpendiculares ao plano $\alpha$**.
>[!Tip] Nota
>Uma reta só é **perpendicular a um plano num ponto P** se e só se for **perpendicular a pelo menos 2 retas do plano que passam em P**.

![[Pasted image 20250130231510.png|250]]

### Vetor paralelo a um plano
Um vetor $\vec v$ é **paralelo ao plano $\alpha$**, se $\vec v$ for nulo ou se **$\vec v$ for vetor diretor de uma reta do plano**.
![[Pasted image 20250130231755.png|300]]
### Posição relativa de dois planos
No espaço, dois planos podem ser:
- paralelos (estritamente paralelos ou coincidentes)
  ![[Pasted image 20250130232619.png|400]]
- concorrentes (perpendiculares ou oblíquos)
  ![[Pasted image 20250130232630.png|400]]
#### Planos paralelos
Dois planos $\alpha$ e $\beta$ são paralelos se e só se os **vetores normais de cada plano**, $\vec n_\alpha$ e $\vec n_\beta$, forem **colineares** (terem as mesmas coordenadas ou serem múltiplos um do outro).

$$\begin{flalign}& \alpha \parallel \beta \iff \vec n_a \parallel \vec n_\beta &\end{flalign}$$
![[Pasted image 20250130233326.png|390]]

#### Planos perpendiculares
Dois planos $\alpha$ e $\beta$ são perpendiculares se e só se os **vetores normais de cada plano**, $\vec n_\alpha$ e $\vec n_\beta$ forem **perpendiculares**.

$$\begin{flalign}& \alpha \perp \beta \iff \vec n_\alpha \perp \vec n_\beta &\end{flalign}$$


![[Pasted image 20250130233336.png|280]]
## Equação cartesiana do plano no espaço
Sejam $\alpha$ um plano, $\vec n$ um vetor não nulo normal ao plano e $P_0$ um ponto do plano.
Um qualquer **ponto $P$** do espaço **pertence ao plano $\alpha$** se e só se os vetores $\vec {P_0 P}$ e $\vec n$ forem **perpendiculares**, ou seja:
$$\begin{flalign}& P \in \alpha \iff \vec{P_0 P} \cdot \vec n=0 &\end{flalign}$$

Fixado um referencial o.n. do espaço e considerando $\vec n(a,b,c)$ e $\vec {P_0}(x_0,y_0,z_0)$, a **equação cartesiana** do plano definida pelo conjunto dos pontos $\vec P(x,y,z)$, que passa em $\vec {P_0}(x_0,y_0,z_0)$ e de que $\vec n (a,b,c)$ é vetor normal é:

$\vec{P_0 P} \cdot \vec n =0\iff$
$$\begin{flalign}& \iff a(x-x_0)+b(y-y_0)+c(z-z_0)=0 &\end{flalign}$$
ou
$$\begin{flalign}& ax+by+cz+d=0 &\end{flalign}$$
![[Pasted image 20250130231257.png|400]]
