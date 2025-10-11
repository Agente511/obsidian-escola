## Conjuntos
### Simbologia
- **Conjunto**: $A$, $B$, $C$, $D$, $F$...
- **Elementos do conjunto**: $a$, $b$, $c$...
- **Universo**: $U$ ou $E$
-  **Conjunto vazio** (não tem elementos): $\{\ \}$ ou $\emptyset$
${}$
- Seja **$A$** um **conjunto** e **$x$** um **elemento**, então:
	- se **$x$ pertence a $A$**: $x \in A$
	- se **$x$ não pertence a $A$**: $x \notin A$

### Formas de definir um conjunto
- ##### Por extensão
	**Enumeração explícita dos elementos** que constituem o conjunto.
	>[!Note] Exemplo
	>O conjunto $A$, constituído pelos números naturais pares inferiores a 4, pode ser definido por:
	>$A=\{0,\ 2\}$

- ##### Por compreensão
	**Condição verificada por todos os elementos** que constituem o conjunto.
	>[!Note] Exemplo
	>O conjunto $A$, constituído pelos números naturais pares inferiores a 4, pode ser definido por:
	>$A=\{x \in \mathbb N: x<4\}$

### Subconjunto
Se **todos os elementos de $A$** são também **elementos de $B$**, então **$A$ está contido em B** e diz-se que **$A$ é um subconjunto de $B$**:
- Se $\forall\ x,\ x \in A \Rightarrow x \in B$, então $A \subset B$
## Operações com conjuntos
- ##### Reunião de $A$ com $B$
	Conjunto de **todos os objetos** que **pertencem pelo menos a um dos conjuntos $A$ e $B$**.
	
	$A \cup B=\{x:\ x \in A\ \lor\ x \in B\}$ 
	![[Pasted image 20251011165602.png|160]]
- ##### Interseção de $A$ com $B$
	Conjunto de **todos os objetos** que **pertencem simultaneamente a $A$ e a $B$**.
	
	$A \cap B=\{x:\ x \in A\ \land\ x \in B\}$
	![[Pasted image 20251011165949.png|160]]
- ##### Complementar de $A$
	Conjunto de **todos os elementos de $U$** que **não pertencem a $A$**.
	
	$\overline A=\{x:\ x \notin A\}$
	![[Pasted image 20251011170547.png|160]]
- ##### Diferença entre $A$ e $B$
	Conjunto de **todos os objetos de $A$** que **não pertencem a $B$**
	
	$A \backslash B=\{x:\ x \in A\ \land\ x \notin B\}$ ou $A \backslash B=\{x\in A: x \notin B\}$
	![[Pasted image 20251011170952.png|160]]

### Propriedades das operações sobre conjuntos
#### Inclusão
>[!Summary] Teorema da inclusão
>Dados dois conjuntos, $A$ e $B$, contidos num universo $U$ e sendo $A \subset B$, temos que:
>- $A \cap B=A$
>- $A \cup B=B$

Verifica-se ainda que:
- O **conjunto vazio** está **contido em qualquer conjunto**
- Se **$A \subset B$**, então **$\overline B \subset \overline A$**

#### Interseção e reunião
Sejam $A$, $B$ e $C$ subconjuntos de um universo $U$, tem-se que:

| Propriedades                      | **Interseção**                                                                                                | **Reunião**                                                                                     |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Comutativa                        | $$A \cap B = B \cap A$$                                                                                       | $$A \cup B = B \cup A$$                                                                         |
| Associativa                       | $$(A \cap B) \cap C = A \cap (B \cap C)$$                                                                     | $$(A \cup B) \cup C = A \cup (B \cup C)$$                                                       |
| Existência de elemento neutro     | **$U$** é o **elemento neutro da interseção**: $$U \cap A = A \cap U = A$$                                    | **$\emptyset$** é o **elemento neutro da reunião**: $$\emptyset \cup A = A \cup \emptyset = A$$ |
| Existência de elemento absorvente | **$\emptyset$** é o **elemento absorvente da interseção**: $$\emptyset \cap A= A \cap \emptyset = \emptyset$$ | **$U$** é o **elemento absorvente da reunião**: $$U \cup A = A \cup U = U$$                     |
| Idempotência                      | $$A \cap A = A$$                                                                                              | $$ A \cup A = A$$                                                                               |
|                                   | <br>**Interceção em relação à reunião**                                                                       | <br>**Reunião em relação à interseção**                                                         |
| Distributiva                      | $$A \cap (B \cup C)=(A \cap B) \cup (A \cap C)$$                                                              | $$A \cup(B \cap C)=(A \cup B) \cap (A \cup C)$$                                                 |
|                                   |                                                                                                               |                                                                                                 |
##### Leis de Morgan para conjuntos
- $\overline {A \cap B}=\overline A \cup \overline B$
- $\overline {A \cup B} = \overline A \cap \overline B$
### Produto cartesiano entre conjuntos
Sejam $A$ e $B$ subconjuntos de $U$, o **produto de cartesiano de $A$ por B** é o conjunto:
$A \times B=\{ (a,\ b):\ a \in A\ \land\ b \in B\}$

>[!Note] Exemplo
>Sejam:
>- $A=\{1,\ 2\}$
>- $B=\{\square, \circ, \triangle \}$
>  
>Tem-se que:
>$A \times B=\{(1,\square),(1,\circ),(1,\triangle),(2,\square),(2,\circ),(2,\triangle)\}$
