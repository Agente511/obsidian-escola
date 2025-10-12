### Cardinal de um conjunto
**Número de elementos** de um conjunto $A$.
Representa-se por **#**.

>[!Note] Exemplo
>Seja $A=\{1, 2, 3\} \subset U$, tem-se que #$A=3$.
## Princípios fundamentais de contagem
- ### Conjuntos equipotentes
	Dois conjuntos são **equipotentes** (têm o **mesmo cardinal**), se e só se, existe uma **bijeção de $A$ sobre $B$**.
	
	>[!Note] Exemplo
	>Sejam:
	>- $A=\{1,\ 2,\ 3\}$
	>- $B=\{\square, \circ, \triangle \}$
	>
	>![[Pasted image 20251012124155.png|220]]
	>
	>Tem-se que:
	>#$A=\{3\}$, #$B=\{3\}$ e #$A=$#$B$, logo $A$ e $B$ são equipotentes.
- ### Princípio geral da adição
	Dados dois conjuntos $A$ e $B$ tais que **$A \cap B = \emptyset$** (**não têm elementos em comum**), tem-se que **#$(A \cup B)=$ #$A\ +$ #$B$**.
	
	>[!Summary] Aplicando ao cálculo combinatório:
	>Se para realizar um processo existirem **duas alternativas que se excluem mutuamente**, e se existirem **$n_1$ maneiras de realizar a alternativa 1** e **$n_2$ maneiras de realizar a alternativa 2**, então o processo pode ser realizado de **$n_1+n_2$ maneiras diferentes**.
- ### Princípio geral da multiplicação
	Dados dois conjuntos $A$ e $B$, sendo os seus respetivos cardinais números naturais (#$A=n$ e #$B=m$, $m,n \in \mathbb N$), tem-se que **#$(A \times B)=$ #$A\times$ #$B=n \times m$**.
	
	>[!Summary] Aplicando ao cálculo combinatório:
	>Se, num processo constituído por **duas etapas**, existirem **$n_1$ maneiras de realizar a etapa 1** e, **para cada uma destas**, **existirem $n_2$ maneiras de realizar a etapa 2**, então todo o processo pode ser realizado de **$n_1 \times n_2$ maneiras diferentes**.

## Arranjos e combinações
### Arranjos com repetição
Chama-se **arranjos com repetição de $n$ elementos $p$ a $p$** ao número de sequências de $p \in \mathbb N_0$ elementos, **não necessariamente distintos**, escolhidos num conjunto de cardinal $n \in \mathbb N$,

Representa-se por **$^nA'_p$**.

Dados $n$ objetos, existem exatamente $^nA'_p$ formas distintas de efetuar $p$ extrações sucessivas de um desses objetos, **repondo o objeto escolhido após cada uma das extrações**.

>[!Summary] Propriedade
>$^nA'_p=n^p$

>[!Note] Exemplo
>>Quantos códigos de 4 dígitos é possível escrever?
>
>$10 \times 10 \times 10 \times 10 = 10^4 = ^{10}A'_4=10 000$

>[!Tip] Nota - Calcular número de subconjuntos de um conjunto $A$
>$$\begin{flalign}&  &\end{flalign}$$
### Permutações
A uma maneira de **ordenar $n$ elementos distintos** dá-se o nome de **permutação dos $n$ elementos**.

Representa-se por **$n!$**.
 
> [!Summary] Propriedades
> O número de permutações de $n$ elementos de um conjunto de cardinal $n \geq 1$ é igual a
> $n!=n \times (n-1) \times (n-2) \times ... \times 1$
> 
>Em geral, para qualquer $n \in \mathbb N$, tem-se: $n!=n \times (n-1)!$
>Por convenção, $0!=1$.

### Arranjos sem repetição
Chama-se **arranjos sem repetição de $n$ elementos $p$ a $p$** ao número de sequências de $p \in \mathbb N_0$ elementos **distintos**, escolhidos num conjunto de cardinal $n \in \mathbb N$, com $n \geq p$.

Representa-se por **$^nAp$**.

Dados $n$ objetos, existem exatamente $^n A_p$ formas distintas de efetuar $p$ extrações sucessivas de um desses objetos, **sem repor o objeto escolhido após cada uma das extrações**.

>[!Summary] Propriedades
>$^nA_p=n \times (n-1) \times ... \times (n-p+1) \text{, com } 0 \leq p \leq n$
>
$$\begin{flalign}& ^nA_p=\frac {n!} {(n-p)!} \text{, com } 0 \leq p \leq n &\end{flalign}$$

>[!Note] Exemplo
>>Quantos códigos de 4 dígitos é possível escrever, de modo que nenhum dígito se repita?
>
>$10 \times 9 \times 8 \times 7 = ^{10}A_4=5040$
### Combinações