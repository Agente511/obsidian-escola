---
Volume: M9
tags:
  - Física
---
## Geradores de corrente contínua
Para que haja corrente elétrica num circuito fechado, é **necessário um gerador**.
Os geradores são dispositivos capazes de **manter uma [[M6 - Circuitos elétricos e grandezas elétricas#Diferença de potencial elétrico/Tensão elétrica ($U$)|diferença de potencial elétrico]]** entre os seus terminais.

Num circuito elétrico os **portadores de carga elétrica**, no seu movimento, **perdem energia ao atravessarem resistências** (os fios de ligação praticamente não perdem energia, pois a sua resistência é considerada desprezável). Parte dessa energia é **dissipada por [[M7 - Potência elétrica#Efeito Joule|efeito Joule]]** na resistência.
Como um gerador tem uma **resistência interna**, $r$, **dissipa energia por efeito Joule**. Assim, a energia dos portadores de carga elétrica no circuito exterior, que é dissipada na resistência $R$, é **inferior à energia transformada no gerador**.
## Força eletromotriz (f.e.m.) de um gerador
Quando se diz que uma pilha é de 9V, refere-se à sua força eletromotriz. Isto significa que um gerador (eletroquímico) com a força eletromotriz de 9V transforma 9J de energia química em energia elétrica, por cada unidade de carga elétrica que o atravessa.
Ou seja, a força eletromotriz é a **energia que o gerador transforma, por unidade de carga elétrica que o atravessa**.
>[!Summary] Cálculo da força eletromotriz
>$$\begin{flalign}& \epsilon = \frac E {|q|} &\end{flalign}$$
>Sendo:
>- $\epsilon$: força eletromotriz (V)
>- $E$: energia (J)
>- $|q|$: módulo da carga elétrica (C)
## Relação da resistência interna com a diferença de potencial elétrico
A força eletromotriz pode ser medida **ligando diretamente os polos do gerador a um voltímetro**, num **circuito aberto**.
No entanto, ao se ligar aos polos de um gerador num **circuito fechado**, o voltímetro indicará uma **tensão inferior ao valor da força eletromotriz** do gerador. Isto deve-se ao facto de alguma energia se dissipar no próprio gerador, por efeito Joule, devido à sua **resistência interna**.
Só um **gerador ideal**, com resistência interna nula, seria capaz de manter nos terminais do circuito exterior, uma tensão elétrica igual ao valor da sua força eletromotriz.

Por essa razão, a **tensão, U, nos terminais de um gerador depende do valor da sua resistência interna**
>[!Summary] Cálculo da diferença de potencial elétrico
>$$\begin{flalign}& U = \epsilon - r I &\end{flalign}$$
>Sendo:
>- $U$: diferença de potencial elétrico (V)
>- $\epsilon$: força eletromotriz (V)
>- $r$: resistência interna do gerador ($\ohm$)
>- $I$: corrente elétrica (A)

#### Curva característica do gerador
![[Pasted image 20240501192115.png]]

A ordenada na origem é a força eletromotriz, $\epsilon$, e o módulo do declive da reta é a resistência interna, $r$, do gerador:
- Em **circuito aberto**, $I=0$. Logo, $U=\epsilon$, ou seja, a **tensão elétrica nos terminais de um gerador é igual à sua força eletromotriz**
- Em **circuito fechado**, como $I\neq0$, tem-se que $U<\epsilon$, ou seja, a **tensão elétrica nos terminais de um gerador é inferior à sua força eletromotriz**
## Balanço da energia num circuito com um gerador e uma resistência pura
Pela [[M4 - Conservação de energia mecânica#Lei da conservação da energia mecânica|Lei da Conservação da Energia]], a **energia transformada no gerador em energia elétrica**, $E_g$, é igual à **soma da energia que o gerador fornece ao circuito exterior**, energia útil, $E_u$, **com a energia que dissipa** por efeito Joule, $E_d$, no seu interior.
>[!Summary] Cálculo da energia transformada no gerador
>$$\begin{flalign}& E_g = E_u + E_d &\end{flalign}$$
>Sendo:
>- $E_g$: energia transformada no gerador (J)
>- $E_u$: energia útil (J)
>- $E_d$: energia dissipada (J)

>[!Summary] Cálculo da potência do gerador
>$$\begin{flalign}& P_g = P_u + P_d &\end{flalign}$$
>Sendo:
>- $P_g$: potência do gerador (W)
>- $P_u$: potência útil (W)
>- $P_d$: potência dissipada (W)
### Energia do gerador
Energia que o gerador transforma em energia elétrica.
>[!Summary] Cálculo da energia do gerador
>$$\begin{flalign}& E_g = \epsilon I \Delta t &\end{flalign}$$
### Energia útil
Energia fornecida pelo gerador ao circuito exterior.
>[!Summary] Cálculo da energia útil
>$$\begin{flalign}& E_u = UI \Delta t &\end{flalign}$$
>ou
>$$\begin{flalign}& E_u = RI^2 \Delta t &\end{flalign}$$
>Sendo:
>- $E_u$: energia útil (J)
>- $U$: diferença de potencial elétrico **nos terminais do gerador** (U)
>- $R$: resistência ($\ohm$)
>- $I$: corrente elétrica (A)
>- $\Delta t$: intervalo de tempo (s)
### Energia dissipada no gerador
Parte da energia que o gerador transforma é dissipada pela resistência interna do próprio gerador.
>[!Summary] Cálculo da energia dissipada no gerador
>$$\begin{flalign}& E_d = rI^2 \Delta t &\end{flalign}$$
>Sendo:
>- $E_d$: energia dissipada (J)
>- $r$: resistência interna ($\ohm$)
>- $I$: corrente elétrica (A)
>- $\Delta t$: intervalo de tempo (s)

>[!Warning] Importante
>Se dividirmos as expressões anterior por $\Delta t$, obtêm-se as **expressões correspondentes para as potências**. (Fórmulas iguais mas sem o $\Delta t$)


>[!Summary] Cálculo da corrente elétrica
>$$\begin{flalign}& I = \frac \epsilon {R+r} &\end{flalign}$$
>Sendo:
>- $I$: corrente elétrica (A)
>- $\epsilon$: força eletromotriz (V)
>- $R$: resistência exterior ($\ohm$)
>- $r$: resistência interna ($\ohm$)

