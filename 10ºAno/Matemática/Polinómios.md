## Operações com polinómios (adição, subtração e multiplicação)
---
*Aquelas contas normais com polinómios que já tinhas aprendido em anos anteriores*
## Divisão inteira de polinómios
---

> [!Summary] Aplicação do algoritmo da divisão inteira de polinómios
> > [!Note] Exemplo
> > $\ \ \ \ \ 6x^2+5x+4 \begin{array}{|r} 2x+1 \\ \hline \end{array}$
> > $\begin{array}{} -6x^2-3x \ \ \ \ \ \ \ \\ \hline \end{array}$
> > $\begin{array}{} \ \ \ \ \ \ \ \ \ \ \ \ \ \  2x+4 \\ \ \ \ \ \ \ \ \ \ \ -2x-1 \\ \hline \end{array}$
> > $\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ 3$
> 
> 1. Escreve-se o **polinómio dividendo à esquerda** (neste caso, $6x^2+5x+4$) do **polinómio divisor** ($2x+1$), ordenando os termos de ambos por **ordem decrescente de grau**.
>    >[!Tip] Nota
>    >Se o **polinómio dividendo for incompleto**, escrevem-se os **monómios omissos com coeficiente 0**.
>2. **Divide-se o monómio de maior grau do dividendo** ($6x^2$) pelo **monómio de maior grau do divisor** ($2x$). Escreve-se o resultado ($3x$) abaixo do divisor.
>3. **Multiplica-se o resultado** obtido ($3x$) pelo **divisor** ($2x+1$). O resultado ($6x^2+3x$) é escrito abaixo no seu simétrico ($-6x^2-3x$).
>4. **Subtrai-se** o resultado obtido ao dividendo. Escreve-se o resultado ($2x+4$) abaixo.
>5. Repete-se os passos anteriores até se obter um polinómio de grau inferior ao grau do polinómio divisor.

## Regra de Ruffini (Divisão de um polinómio por $x-a$)
---
> [!Summary] Aplicação da Regra de Ruffini
> > [!Note] Exemplo
> > Determinar o quociente e o resto da divisão inteira do polinómio $A(x)=x^3-3x^2-4x+6$ pelo polinómio $B(x)=x-2$.
> > 
> > $\begin{array}{r|*{4}{c}} & 1 & -3 & -4 & 6 \\ \\ 2 & & 2 & -2 & -12 \\ \hline & 1 & -1 & -6 & -6=R \\ \end{array}$
> > >*(ignora as linhas verticais além da 1ª, não é suposto pôr essas)* *(o resto deve estar rodeado por umas linhas tipo "L")*
> > 
> > $Q(x)=x^2-x-6$
> > $R(x)=-6$
> 
> 1. Escreve-se os **coeficientes do dividendo na primeira linha** ($1, -3, -4$ e $6$), ordenados por ordem decrescente de grau, e **$a$ na segunda linha, à esquerda**
> 2. Escreve-se o **1º coeficiente do dividendo** ($1$) **na linha de baixo**.
> 3. **Multiplica-se $a$ ($2$) pelo número da última linha ($1$)** e coloca-se o resultado ($2$) na segunda linha, na coluna seguinte.
> 4. **Soma-se os valores dessa coluna** ($-3 e 2$) e escreve-se o resultado ($-1$), na última linha, na mesma coluna.
> 5. Repete-se o passo 4.
> 6. Quando se conseguirem todos os valores da última linha, os primeiros números são os **coeficientes do polinómio quociente** e o último número é o **resto**.

## Teorema do resto
---
>[!Summary] Teorema do resto
>Dado um polinómio $P(x$) e um número real $\alpha$, o **resto da divisão inteira de $P(x)$ por $x-a$** é **igual a $P(x$)**.

>[!Note] Exemplo
>- Dado o polinómio $P(x)=x^3-2x^2+3x+5$, determine o resto da sua divisão por $x+3$.
>  $P(-3)=(-3)^3-2(-3)^2+3(-3)+5=-49$
>  $R(x)=-49$

## Raiz/Zero de um polinómio
---
Seja $P(x)$ um polinómio. Designa-se por "raiz do polinómio $P(x)$" qualquer número real $\alpha$ tal que $P(\alpha)=0$

>[!Tip] Nota
>As raízes ou zeros de um polinómio $P(x)$ são as soluções da equação $P(x)=0$.

## Fatorização de polinómios
---
>[!Note] Exemplos
>- Colocar em evidência: $P(x)=x^3+2x^2+3x=x(x^2+2x+3)$
>- Diferença de quadrados: $P(x)=x^2-4=(x-2)(x+2)$
>- Quadrado da soma: $P(x)=x^2+2x+1=(x+1)^2=(x+1)(x+1)$
>- Quadrado da diferença: $P(x)=x^2-8x+16=(x-4)^2=(x-4)(x+4)$
>- Divisor(es) $\times$ Quociente: $P(x)=(x-\alpha) \times Q(x)$
>- 

## Multiplicidade de uma raiz
---
A multiplicidade de $\alpha$ é o maior número natural $n$ para o qual existe um polinómio $Q(x)$ tal que $P(x)=(x-\alpha)^n \times Q(x)$.

>[!Tip] Nota
>No caso de $n$ ser **1** diz-se que $\alpha$ é uma **raiz simples**.
>No caso de $n$ ser **2** diz que $\alpha$ é uma **raiz dupla**.

>[!Note] Exemplo
>$\begin{array}{r|*{5}{c}} & 2 & 4 & -1 & -6 & -3 \\ \\ -1 & & -2 & -2 & 3 & 3 \\ \hline & 2 & 2 & -3 & -3 & 0=R \\ \\ -1 & & -2 & 0 & 3 \\ \hline & 2 & 0 & -3 & 0=R \\ \\ -1 & & -2 & 2 \\ \hline & 2 & -2 & -1=R \end{array}$
>>*(ignora as linhas verticais além da 1ª, não é suposto pôr essas)* *(o resto deve estar rodeado por umas linhas tipo "L")*
>
>
>Decompondo obtém-se $P(x)=(x+1)^2\times(2x-2)$. A raiz 1 tem multiplicidade 2 (é uma raiz dupla).


