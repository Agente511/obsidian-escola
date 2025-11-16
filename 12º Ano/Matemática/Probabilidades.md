## Experiências e espaço amostral
### Conceitos
- ##### Universo de resultados ou espaço amostral
	Resultados de uma experiência.
	Os elementos chamam-se **casos possíveis**.
	Representa-se habitualmente por $\Omega$, $E$ ou $S$.
- ##### Experiência determinista
	Experiência **com resultado conhecido**.
	Tem apenas **1 caso possível**.
- ##### Experiência aleatória
	Experiência **sem resultado conhecido**, apesar de ser um dos elementos do espaço amostral.
	Tem **múltiplos casos possíveis**.
	>[!Exemplo]
	>> Lançar três moedas equilibradas ao ar e anotar as faces que ficam voltadas para cima.
	>
	>Usando o **diagrama de árvore** para determinar o espaço amostral desta experiência e considerando N: "face nacional" e E: "face europeia":
	>![[Pasted image 20251022135253.png]]
	>
	>$\Omega = \{(N, N, N),\ (N, N, E),\ (N, E, N),\ (N, E, E),\ (E, N, N),\ (E, N, E),\ (E, E, N),\ (E, E, E)\}$
	>$\# \Omega = 2 \times 2 \times 2 =8$ 
	>
	>>Lançar dois dados equilibrados, um preto e um branco, e verificar as faces que ficam voltadas para cima.
	>
	>Usando a **tabela de dupla entrada** para determinar o espaço amostral desta experiência:
	>![[Pasted image 20251022134758.png]]
	>
	>$\Omega= ...$
## Acontecimentos
Cada um dos **subconjuntos do espaço amostral** designa-se por acontecimento.
Os elementos de um acontecimento designam-se por **casos favoráveis**.

- **Acontecimento impossível**: Conjunto vazio
- **Acontecimento certo**: Espaço amostral
- **Acontecimento elementar**: Conjunto com um único elemento (1 caso favorável)
- **Acontecimento composto**: Conjunto com mais de um elemento (múltiplos casos favoráveis)
## Operações com acontecimentos
- ##### Acontecimento reunião (ou união) de $A$ com $B$
	Verifica-se quando se realiza $A$ **ou** $B$.
	Representa-se por $A \cup B$
	>[!Note] Exemplo
	>>Lançar um dado cúbico e registar a face que fica voltada para cima.
	>
	>Considerando os acontecimentos:
	>$A$: "Sair um número primo."  $\ \ \ \ A=\{2,\ 3,\ 5\}$
	>$B$: "Sair um número par." $\ \ \ \ \ \ \ \ \ B=\{2,\ 4,\ 6\}$
	>
	>$A \cup B$: "Sair um número primo **ou** um número par."
	>$A \cup B= \{2,\ 3,\ 5\} \cup \{2,\ 4,\ 6\}=\{2,\ 3,\ 4,\ 5,\ 6\}$
	>

- ##### Acontecimento interseção de $A$ com $B$
	Verifica-se quando se realiza $A$ **e** $B$ **em simultâneo**.
	Representa-se por $A \cap B$
	
	>[!Note] Exemplo
	>>Lançar um dado cúbico e registar a face que fica voltada para cima.
	>
	>Considerando os acontecimentos:
	>$A$: "Sair um número primo."  $\ \ \ \ A=\{2,\ 3,\ 5\}$
	>$B$: "Sair um número par." $\ \ \ \ \ \ \ \ \ B=\{2,\ 4,\ 6\}$
	>
	>$A \cup B$: "Sair um número primo **e** um número par."
	>$A \cup B= \{2,\ 3,\ 5\} \cap \{2,\ 4,\ 6\}=\{2\}$

- ##### Diferença
	Representa-se por $A \backslash B$
### Acontecimentos incompatíveis, disjuntos ou mutuamente exclusivos
Acontecimentos que **nunca ocorrem em simultâneo**.
A realização de um deles implica a não realização do outro.

$A$ e $B$ dizem-se **incompatíveis** se e só se $A \cap B = \emptyset$.
- ##### Acontecimentos contrários ou complementares
	$A$ e $B$ dizem-se **contrários** se $A \cap B= \emptyset$ e $A \cup B=\Omega$, isto é, se o acontecimento reunião  de $A$ com $B$ corresponder ao espaço amostral e os acontecimentos forem incompatíveis.

### Acontecimentos equiprováveis
Acontecimentos com a **mesma probabilidade**.
## Lei de Laplace
>[!Summary] Definição de Laplace de probabilidade
>Numa experiência aleatória onde os casos possíveis são em número finito e equiprováveis, a probabilidade de um acontecimento $A$ é dada pelo quociente entre o número de casos favoráveis a esse acontecimento e o número de casos possíveis.
>
>$$\begin{flalign}& P(A) = \frac {\text{N.º de casos favoráveis a } A} {\text{N.º de casos possíveis}} = \frac {\#A} {\#E} &\end{flalign}$$

>[!Info] Notas
>- $0 \leq P(A) \leq 1$ ou $0\% \leq P(A) \leq 100\%$
>- $P(\text{acontecimento certo})=P(E)=1$
>- $P(\text{acontecimento impossível})=P(\emptyset)=0$

## Propriedades das probabilidades
>[!Summary] Propriedades das probabilidades
>- $0 \leq P(A) \leq 1$
>- $P(\emptyset)=0$ e $P(E)=1$
>- $P(\overline A)= 1 - P(A)$
>- Se $A \subset B$,
>	- $P(A) \leq P(B)$
>	- $P(B \backslash A)=P(B)-P(A)$
>- $P(A \cup B) = P(A) + P(B) - P(A \cap B)$
>- $P(A) = P(A \cap B) + P(A \cap \overline B)$
>
>Leis de Morgan:
>- $P(\overline {A \cup B}) = P(\overline A \cap \overline B)$
>- $P(\overline {A \cap B}) = P(\overline A \cup \overline B)$

## Probabilidade condicionada

> [!Summary] Definição de probabilidade condicionada
> Dados um conjunto finito, não vazio, $E$, e dois acontecimentos $A$ e $B$ em $E$, com $P(B) \neq 0$, a **probabilidade condicionada de $A$ se $B$**, ou **probabilidade de $A$, sabendo que ocorreu $B$**:
> $\Large \frac {P(A \cap B)} {P(B)}$