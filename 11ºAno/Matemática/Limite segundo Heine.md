## Pontos aderentes a um conjunto de números reais
Um ponto $a$ é um **ponto aderente** de um conjunto de números reais $A$ se existe uma **sucessão ($x_n$) de elementos de $A$** cujo **limite seja $a$** ($\lim x_n=a$).

- Todo o ponto $a$ que pertença a $A$ ($a \in A$) é um ponto aderente de $A$
- $a$ pode ser ponto aderente de $A$ mesmo que $a \notin A$

>[!Note] Exemplo
>![[Pasted image 20250528175739.png|550]]

## Limite segundo Heine: Limite de uma função num ponto aderente ao respetivo domínio
Seja $f$ uma função real de variável real e $a \in \mathbb R$, o número real $b$ designa-se por **limite de $f(x)$ quando $x$ tende para $a$** quando **$a$ é um ponto aderente de $D_f$** e o **limite da sucessão ($x_n$) de elementos do $D_f$ convergente para $a$ é $b$**, ou seja, $\lim f(x_n)=b$, que se escreve $\underset{x\rightarrow a} \lim f(x)=b$.
>[!Tip] Forma mais legível
>Dizemos que **o limite de $f(x)$ quando $x$ tende para $a$ é igual a $b$** se, sempre que **escolhemos valores de $x$ muito próximos de $a$**, os valores correspondentes de **$f(x)$ ficam cada vez mais próximos de $b$**.
>
>Ou seja, se tivermos uma sucessão de números $(x_n)$, todos dentro do $D_f$, e essa sucessão se aproximar de $a$, então os valores $f(x_n)$ devem aproximar-se de $b$.
>
>Escreve-se $\underset{x\rightarrow a} \lim f(x)=b$.


>[!Note] Exemplo
>![[Pasted image 20250528181525.png|550]]

## Limites laterais
### Limite à esquerda
Quando $x$ tende para $a$ por valores inferiores a $a$ (à esquerda de $a$), escreve-se $\underset{x\rightarrow a^-} \lim f(x)=b$.
### Limite à direita
Quando $x$ tende para $a$ por valores superiores a $a$ (à direita de $a$), escreve-se $\underset{x\rightarrow a^+} \lim f(x)=b$.

>[!Note] Exemplo
>![[Pasted image 20250528182843.png|550]]

#### Existência de $\underset{x\rightarrow a} \lim f(x)$
$\underset{x\rightarrow a} \lim f(x)$ existe, se $a$ é um ponto aderente de $D_f$ e
- **$a$ pertence a  $D_f$** ($a \in D_f$) e **$f(a)=\underset{x\rightarrow a^-} \lim f(x)=\underset{x\rightarrow a^+} \lim f(x)$**.
  Neste caso, $\underset{x\rightarrow a} \lim f(x)=f(a)=\underset{x\rightarrow a^-} \lim f(x)=\underset{x\rightarrow a^+} \lim f(x)$.
- **$a$ não pertence a $D_f$** ($a \notin D_f$) e **$\underset{x\rightarrow a^-} \lim f(x)=\underset{x\rightarrow a^+} \lim f(x)$**.
  Neste caso, $\underset{x\rightarrow a} \lim f(x)=\underset{x\rightarrow a^-} \lim f(x)=\underset{x\rightarrow a^+} \lim f(x)$

>[!Note] Exemplos
>![[Pasted image 20250528184254.png|500]]
>![[Pasted image 20250528184316.png|500]]

### Limites no infinito
*(não sai?)*