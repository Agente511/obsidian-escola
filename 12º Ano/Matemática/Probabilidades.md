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
	>> Lançar três moedas equilibradas ao ar e anotas as faces que ficam voltadas para cima.
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
	>
### Acontecimentos incompatíveis, disjuntos ou mutuamente exclusivos
Acontecimentos que **nunca ocorrem em simultâneo**.
A realização de um deles implica a não realização do outro.

$A$ e $B$ dizem-se **incompatíveis** se e só se $A \cap B = \emptyset$.
- ##### Acontecimentos contrários
	$A$ e $B$ dizem-se **contrários** se $A \cap B= \emptyset$ e $A \cup B=\Omega$, isto é, se o acontecimento reunião  de $A$ com $B$ corresponder ao espaço amostral e os acontecimentos forem incompatíveis.
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
