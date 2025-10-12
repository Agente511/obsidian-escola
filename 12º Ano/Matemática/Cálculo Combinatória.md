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
Chama-se **arranjos com repetição de $n$ elementos $p$ a $p$** ao número de sequências de $p \in \mathbb N_0$ elementos, não necessariamente distintos, escolhidos num conjunto de cardinal $n \in \mathbb N$,

Representa-se por **$^nA'_p$**.

>[!Note] Exemplo
>Quantos códigos de 4 dígitos é possível escrever?
>
>>$10 \times 10 \times 10 \times 10 = 
### Permutações
### Arranjos sem repetição
### Combinações