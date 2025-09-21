## Características do movimento circular uniforme
>[!Note] Exemplos de movimentos circulares uniformes
>- Cadeiras numa roda gigante
>- Cadeiras de um carrossel
>- Pás de uma ventoinha elétrica
>- Pás da hélice de um motor
>- Ponteiros de um relógio
#### Velocidade
A **velocidade**, $\vec v$, **não é constante**, porque, como é **tangente à trajetória** em cada instante, a sua **direção varia**. Apenas o **módulo da velocidade permanece constante**. Por esta razão, a **aceleração**, $\vec a$, **não é nula** (apenas o seu módulo).
![[Pasted image 20241110184545.png|200]]
#### Força centrípeta e aceleração centrípeta
A **resultante das forças** que atua sobre o corpo tem:
- **intensidade constante**
- **direção perpendicular à velocidade**, em cada ponto
- **sentido para o centro da trajetória**

Sendo, por isso,  designada **força centrípeta**.

Como $\vec F_R=m\ \vec a$, a **aceleração** também é **perpendicular à velocidade** e com **sentido para o centro da trajetória**. Designa-se, por isso, **aceleração centrípeta**.

![[Pasted image 20241110184556.png|200]]
Logo, têm a mesma direção e sentido.
### Período, $T$
**Tempo** que um corpo demora a efetuar **uma volta** (ou rotação) **completa**.
- Unidade SI: segundo (s)

>[!Note] Cálculo do período
>O período e a frequência são grandezas inversamente proporcionais.
>$$\begin{flalign}& T=\frac 1 f &\end{flalign}$$

Como o movimento é circular uniforme, o **corpo passa diversas vezes pela mesma posição**, com a **mesma velocidade e aceleração**, em **intervalos de tempo iguais**.
### Frequência, $f$
**Número de voltas** (ou rotações) **que um corpo executa por unidade de tempo**.
- Unidade SI: hertz (Hz) ou s$^{-1}$
  >[!Tip] Nota
  >Também é muito usada como unidade o número de **rotações por minuto**, **rpm**, mas **não é uma unidade SI**.
  >$$\begin{flalign}& \text{Hz}=\frac {\text{rpm}} {60} &\end{flalign}$$

>[!Note] Cálculo da frequência
>O período e a frequência são grandezas inversamente proporcionais.
>$$\begin{flalign}& f=\frac 1 T &\end{flalign}$$

### Velocidade angular, $\omega$
**Ângulo descrito por unidade de tempo**.
- Unidade SI: radiano por segundo (rad/s ou rad s$^{-1}$)

>[!Note] Cálculo da velocidade angular
>$$\begin{flalign}& \omega=\frac {\Delta \theta} {\Delta t} &\end{flalign}$$
>ou
>$$\begin{flalign}& \omega=\frac {2\pi} {T} &\end{flalign}$$
>ou
>$$\begin{flalign}& \omega=2\pi f &\end{flalign}$$
>Sendo:
>- $\Delta \theta$: ângulo descrito entre A e B (rad)
>- $\Delta t$: intervalo de tempo (s)
### Velocidade linear, $v$
Coincide com a rapidez média, por se tratar de um movimento uniforme.
- Unidade SI: metro por segundo (m/s)

>[!Note] Cálculo da velocidade linear
>$$\begin{flalign}& v=\frac {2\pi r} T &\end{flalign}$$
>ou
>$$\begin{flalign}& v=\omega r &\end{flalign}$$
>Sendo:
>- r: raio da trajetória circular (m)

O módulo da velocidade linear, $v$, é diretamente proporcional ao raio, $r$, da trajetória.
>[!Tip] Nota
>O módulo da **velocidade média** de **uma volta completa** será **nula**, porque o deslocamento é nulo.
### Aceleração centrípeta, $a_c$
Relaciona-se com o módulo da velocidade (linear ou angular) e com o raio da circunferência.
- Unidade SI: metro por segundo ao quadrado (m/s$^2$)

>[!Note] Cálculo da aceleração centrípeta
>$$\begin{flalign}& a_c=\frac {v^2} r &\end{flalign}$$
>ou
>$$\begin{flalign}& a_c=\omega^2\ r &\end{flalign}$$
>Sendo:
>- r: raio da trajetória circular (m)
## Movimento circular uniforme de um satélite em órbita terrestre
A **única força** que atua sobre um **satélite à volta da Terra** é a **força gravítica**.
Se **não existisse força gravítica**, a **resultante das forças** que atua sobre os satélites **seria nula** e, pela [[M5 - Segunda e Primeira Lei de Newton#Primeira Lei de Newton (ou Lei da Inércia)|Primeira Lei de Newton]], os satélites passariam a ter um **movimento retilíneo uniforme** com velocidade igual à que tinham inicialmente, **perdendo-se no Espaço**.

É necessária que o **satélite** seja **lançado com uma velocidade inicial** para entrar em órbita
- Se um satélite foi lançado com uma **velocidade menor** do que a mínima necessária para entrar em órbita, **cairia na Terra**.
- Se fosse lançado com uma **velocidade muito maior**, **escaparia da gravidade da Terra** e perder-se-ia no Espaço.

> [!Info] +Info
> Os satélites permanecem em órbita à volta da Terra com uma velocidade entre 11000 km/h e 27000 km/h, aproximadamente.

> [!Note] Cálculo do módulo da velocidade de um satélite em órbita
> Recorrendo à [[M5 - Segunda e Primeira Lei de Newton|Segunda Lei de Newton]] e à [[M3 - Lei da Gravitação Universal e Terceira Lei de Newton#Lei da Gravitação Universal|Lei da Gravitação Universal]], tem-se:
> $$\begin{flalign}&  m\ a_c = G\frac {M_T\ m} {r^2} \iff a_c = G\frac {M_T} {r^2} \iff \frac {v^2} {r} = G\frac {M_T} {r^2} \iff &\end{flalign}$$
> $$\begin{flalign}& \iff v=\sqrt \frac {G\ M_T} r &\end{flalign}$$
> Sendo o **raio da órbita**, $r$, igual ao **raio da terra**, $R_T$, **somado com a altura**, $h$, a que o satélite se encontra, o **módulo da velocidade do satélite em órbita** também pode ser calculado pela expressão:
> $$\begin{flalign}& v=\sqrt \frac {G\ M_T} {R_T+h} &\end{flalign}$$

O **módulo da velocidade**, $v$, de um **satélite** em órbita **não depende da massa do satélite** e **diminui quanto maior for a altitude**, $h$, a que o satélite se encontra.
## Satélites geoestacionários
Satélites que **orbitam no plano do equador** descrevendo uma órbita circular com um **período de translação igual ao período de rotação da Terra**, ou seja, **24 horas** (86400 s). Por esta razão, um satélite geoestacionário encontra-se sempre na **mesma posição relativamente a um ponto qualquer da superfície terrestre**.

>[!Tip] Nota
>São usados para comunicações, meteorologia, aplicações militares, investigação espacial, etc.
