## Conceito de sucessão
![[Pasted image 20250212174646.png|400]]
Uma **sucessão** (real) é uma **função de domínio $\mathbb N$** e **conjunto de chegada $\mathbb R$**.
O **contradomínio** é o **conjunto dos termos da sucessão**.

A **sucessão $u$** representa-se por ($u_n$) $n \in \mathbb N$, ou simplesmente **$(u_n)$**.
### Linguagem e notação
**Termos** = imagens
**Ordem** = objetos
>[!Note] Exemplo
>A imagem de 2 é designada por **segundo termo** e representa-se por **$u_2$**.

A $u(n)$ (**imagem de $n$**) representa-se por **$u_n$** e designa-se por **termo geral de sucessão**.

>[!Note] Exemplo
>Na sucessão $u(n)=\sqrt n +1$ tem-se:
>![[Pasted image 20250212180358.png|500]]

### Sequência
Uma sequência é uma **sucessão** com um **número finito de termos**.
## Gráfico de uma sucessão
Pode-se representar o gráfico de uma sucessão num referencial cartesiano, como o conjunto de pontos da reta da equação cujas **abcissas são os números naturais**.

>[!Note] Exemplo
>Seja $(u_n)$ a sucessão de termo geral $u_n=\frac {n+1} 2$, o seu gráfico é o conjunto de pontos da reta de equação $y=\frac {x+1} 2$ cujas abcissas são os números naturais.
>![[Pasted image 20250212193207.png|300]]

## Majorantes e minorantes de um conjunto de números reais
### Majorante de um conjunto
Seja $A$ um conjunto de números reais:
- Um número real $M$ é **majorante** de $A$ se $\forall a \in A, a \leq M$ (todos os números do conjunto forem menores ou iguais a $M$).
- O conjunto $A$ é **majorado** se tiver **pelo menos um majorante**.

>[!Note] Exemplos
>- O intervalo de números reais $[4,7]$ é **majorado**, tendo como **majorantes** todos os **números superiores ou iguais a 7**. $[7, +\infty[$ é o conjunto dos majorantes do conjunto
>- O intervalo de números reais $[4,7[$ é **majorado**, tendo como **majorantes** todos os **números superiores ou iguais a 7**. $[7, +\infty[$ é o conjunto dos majorantes do conjunto..
>- O conjunto $A={1,2,3}$ é **majorado**, tendo como **majorantes** todos os **números superiores ou iguais a 3**. $[3, +\infty[$ é o conjunto dos majorantes do conjunto.
>- O intervalo de números reais $[3, +\infty[$ **não é majorado**, porque **não tem majorantes**.
>- O conjunto $\mathbb N$ **não é majorado**, porque **não tem majorantes**.
#### Máximo de um conjunto
Seja $A$ um conjunto de números reais:
- Um número real é **máximo de $A$** se **pertencer a $A$** e for **majorante de $A$**.

>[!Note] Exemplos
>- **7 é máximo** do intervalo de números reais **$[4,7]$**, pois **7 pertence ao conjunto** e **7 é majorante deste conjunto**.
>- **7 não é máximo** (nem nenhum outro número é) do intervalo de números reais **$[4,7[$**, pois **7 $\notin [4,7[$**, apesar de ser **majorante** deste conjunto.

Um conjunto só pode ter **um único máximo**.
### Minorante de um conjunto
Seja $A$ um conjunto de números reais:
- Um número real $m$ é **minorante** de $A$ se $A$ se $\forall a \in A, a \geq m$ (todos os números do conjunto forem maiores ou iguais a $m$).
- Diz-se que $A$ é **minorado** se tiver **pelo menos um minorante**.

>[!Note] Exemplos
>- O intervalo de números reais $[4,7]$ é **minorado**, tendo como **minorantes** todos os **números inferiores ou iguais a 4**. $]-\infty, 4]$ é o conjunto dos minorantes do conjunto.
>- O intervalo de números reais $]4,7]$ é **minorado**, tendo como **minorantes** todos os **números inferiores ou iguais a 4**. $]-\infty, 4]$ é o conjunto dos minorantes do conjunto.
>- O intervalo de números reais $]-\infty,3]$ **não é minorado**, porque **não tem minorantes**. 
>- O conjunto $\mathbb N$ é **minorado**, tendo como **minorantes** todos os **números inferiores ou iguais a 1**.

#### Mínimo de um conjunto
Seja $A$ um conjunto de números reais:
- Um número real é **mínimo de $A$** se **pertencer a $A$** e for **minorante de $A$**.

>[!Note] Exemplos
>- **4 é mínimo** do intervalo de números reais **$[4,7]$**, pois **4 $\in [4,7]$** e **7 é minorante deste conjunto**.
>- **4 não é mínimo** (nem nenhum outro número é) do intervalo de números reais **$]4,7]$**, pois **4 $\notin\ ]4,7]$**, apesar de ser **minorante** deste conjunto.

Um conjunto só pode ter **um único mínimo**.
### Conjunto limitado
Um conjunto é limitado se for **minorado e majorado**.
>[!Note] Exemplos
>- O conjunto ${1,2,3,4,5}$ é **limitado**.
>- O intervalo de números reais $[-1,+\infty]$ **não é limitado**, porque **não é majorado**.
>- O intervalo de números reais $]-\infty, 1]$ **não é limitado**, porque **não é minorado**.
>- O conjunto $\mathbb Z$ **não é limitado**, porque **não é minorado nem majorado**.

## Sucessões monótonas
Uma sucessão é monótona se for **crescente** ou se for **decrescente**.

Uma sucessão $(u_n)$ é:
- **crescente** se e só se $\forall n \in \mathbb N,$ **$u_{n+1}>u_n$**
- **crescente em sentido lato** se e só se $\forall n \in \mathbb N,$ **$u_{n+1} \geq u_n$**
- **decrescente** se e só se $\forall n \in \mathbb N,$ **$u_{n+1}<u_n$**
- **decrescente em sentido lado** se e só se $\forall n \in \mathbb N,$ **$u_{n+1} \leq u_n$**

Pode-se **estudar uma sucessão quanto à monotonia** calculando a **diferença $u_{n+1}-u_n$**:
- **crescente** se **$u_{n+1}-u_n>0$**
- **decrescente** se **$u_{n+1}-u_n<0$**
## Sucessões definidas por recorrência
Um sucessão definida por recorrência quando **se conhece o 1º termo** (ou outro) é a **relação entre o termo seguinte e a recorrência**.
>[!Note] Exemplo
>$$\begin{flalign}& u_1=3 \land u_{n+1}=2u_n+1, \forall n \in \mathbb N &\end{flalign}$$
>ou
>
>$$\begin{cases} u_1=3 \\\ u_{n+1}=2u_n+1, \forall n \in \mathbb N \end{cases}$$
>

