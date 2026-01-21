## Produto cartesiano de dois conjuntos
O **produto cartesiano de A em B** é um **conjunto** constituído por todos os **pares ordenados** em que o **1º elemento pertence a A** e o **2º elemento pertence a B**
>[!Note] Exemplo
>$A =$ {$1, 2, 4$}
>$B=$ {$7, 8$}
>
>#### $A \times B =$ {$(1, 7); (1, 8); (2, 7); (2, 8); (4,7); (4,8)$}
>
>##### $\#A = 3$
>##### $\#B = 2$

## Função
**Função de A em B** é uma correspondência em que a cada elemento de A associa um e um só elemento de B.
![[Pasted image 20240227234622.png|450]]
>[!Note] Exemplo
>$A$ - Conjunto de partida/Conjunto dos objetos/Domínio
>$D_f =$ {$1, 2, 3$}
>
>$B$ - Conjunto de chegada
>
>Conjunto das imagens/Contradomínio - $D'_f =$ {$e, f, g$}
>
>$f(3) = g$ $\leftarrow$ A imagem de $3$ é $g$
#### Diagrama de setas
![[Pasted image 20240227235300.png]]
#### Tabela
| $x$    | 1   | 2   | 3   |
| ------ | --- | --- | --- |
| $f(x$) | $e$ | $f$ | $g$ |
#### Gráfico
$G_f =$ {$(1,e); (2,f); (3,g)$}
## Funções injetivas
Uma função diz-se injetiva quando a **objetos diferentes** correspondem **imagens diferentes**.
>[!Note] Exemplo

| $x$    | 1   | 2   | 3   |
| ------ | --- | --- | --- |
| $f(x$) | $2$ | $4$ | $6$ |
$f$ é uma função injetiva.

| $x$    | 1     | 2   | 3     |
| ------ | ----- | --- | ----- |
| $g(x$) | Ímpar | Par | Ímpar |
$g$ não é uma função injetiva, porque $g(1) = g(3)$.

## Funções sobrejetivas
Uma função diz-se sobrejetiva se o **contradomínio coincidir** com o **conjunto de chegada**.

![[Pasted image 20240228000637.png]]
## Funções bijetivas
Uma função diz-se bijetiva se for **simultaneamente injetiva e sobrejetiva**.

## Composição de Funções

>[!Summary] Caso geral
>![[Pasted image 20240228001204.png|300]]
>Sejam $f$ e $g$ duas funções.
>A função composta de $g$ com $f$ é a função $g \circ f$ tal que:
>- $D_{g \circ f} =$ {$x \in D_f: f(x) \in D_g$}
>- $(g \circ f) (x) = g (f(x))$

>[!Tip] Nota
>$g \circ f$ $\rightarrow$ lê-se "$g$ após $f$"

> [!NOTE] Exemplo
> ![[Pasted image 20240228000816.png|400]]
> $(g\circ f)(4) = g(f(4)) = g(13) = 10$
> $(g\circ f)(3) = g(f(3)) = g(11) = 8$
> $(g\circ f)(2) = g(f(2)) = g(9) = 6$
> $(g\circ f)(1) = g(f(1)) = g(7) = 4$

## Função Identidade
- **Domínio** igual ao **conjunto de chegada**
- A **imagem** de cada objeto é o **próprio objeto**
$Id_A: A \rightarrow A$ tal que $Id_A(x) = x$

Exemplo:

| $x$    | 1   | 2   | 3   |
| ------ | --- | --- | --- |
| $Id_A$ | 1   | 2   | 3   |
$Id_A: A \rightarrow A$
$A=${$1, 2, 3$}

## Função inversa de uma função bijetiva
---
![[Pasted image 20240228191608.png]]
A função inversa de $f$ representa-se por **$f^{-1}$**
- $D_{f^{-1}} = D'_f$
- $D'_{f^{-1}} = D_f$
- $(f^{-1})^{-1} = f$
- $f \circ f^{-1} = Id_B$
- $f^{-1} \circ f = Id_A$
