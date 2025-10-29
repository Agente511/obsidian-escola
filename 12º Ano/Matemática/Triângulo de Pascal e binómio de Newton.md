## Triângulo de Pascal
>[!Summary] Propriedades
>1. $\large ^nC_p=^nC_{n-p}$
>2. $$\begin{flalign}& \large \sum_{p=0}^n\ ^nC_p = 2^n &\end{flalign}$$
>3. $\large ^nC_p+^nC_{p+1}=^{n+1}C_{p+1}$

O triângulo de Pascal pode ser construído indefinidamente com recurso à última propriedade, isto é, somando dois números consecutivos de uma linha obtém-se o número colocado entre eles na linha seguinte.

![[Pasted image 20251012135839.png]]

Cada **elemento** que constitui o triângulo corresponde aos chamados **coeficientes binomiais**, $^nC_p$.
Calculando os respetivos valores dos coeficientes binomiais, o triângulo também pode ser representado da forma seguinte:

![[Pasted image 20251012135947.png]]

>[!Summary] Notas
>1. Cada **linha começa e acaba em 1**.
>   $\large (^nC_0=^nC_n=1)$
>2. Em cada linha, **elementos igualmente afastados dos extremos** são **iguais**.
>   $\large (^nC_p=^nC_{n-p})$
>3. Cada elemento, que **não esteja num dos extremos** de uma linha, é **igual à soma dos elementos que estão acima dele**, na **linha anterior**, um à **esquerda** e outro à **direita**.
>   $\large (^nC_p+^nC_{p+1}=^{n+1}C_{p+1})$
>4. O **segundo e o penúltimo elementos** da linha de ordem $n$ são ambos **iguais a $n$**.
>5. A **soma de todos os elementos da linha** de ordem $n$ é **$2^n$**.
>   $$\begin{flalign}& (\sum_{p=0}^n\ ^nC_p = 2^n) &\end{flalign}$$
>6. A **linha** de ordem $n$ tem **$n+1$ elementos**.
>7. Se **$n$** é 
>	- **par**, a **linha** de ordem $n$ tem um **número ímpar de elementos**, sendo o **maior** deles o **elemento central**, que é $\Large ^nC_{\frac n 2}$
>	- **ímpar**, a **linha** de ordem $n$ tem um **número par de elementos**, sendo os **dois maiores** os **dois elementos centrais**, que são $\Large ^nC_{\frac {n-1} 2}$ e $\Large ^nC_{\frac {n+1} 2}$

## Binómio de Newton
Os **coeficientes do desenvolvimento de $(a+b)^n$** são os **coeficientes binomiais do triângulo de Pascal** e são de forma **$^nC_p$**.

>[!Summary] Termo geral do desenvolvimento de binómio de Newton
>$$\begin{flalign}& \large (a+b)^n=\sum_{p=0}^n\ ^nC_p \times a^{n-p} \times b^p &\end{flalign}$$

>[!Note] Exemplo
>$(a+b)^4=$
>$=^4C_0 \times a^{4-0} \times b^0 + ^4C_1 \times a^{4-1} \times b^1 + ^4C_2 \times a^{4-2} \times b^2 + ^4C_3 \times a^{4-3} \times b^3 + ^4C_4 \times a^{4-4} \times b^4=$
>$=^4C_0 \times a^{4} \times b^0 + ^4C_1 \times a^{3} \times b^1 + ^4C_2 \times a^{2} \times b^2 + ^4C_3 \times a^{1} \times b^3 + ^4C_4 \times a^{0} \times b^4=$
>$=a^{4} + 4 a^{3} b + 6 a^{2} b^2 + 4 a b^3 + b^4=$

Verifica-se que os **expoentes de $a$** variam de **$n$ a 0** e os **expoentes de $b$** variam de **0 a $n$**.

>[!Summary] Notas
>1. O desenvolvimento de $(a-b)^n$ pode ser obtido pela expressão $(a+(-b))^n$.
>2. O desenvolvimento de $(a+b)^n$ tem $(n+1)$ termos.
>3. A soma dos coeficientes binomiais $(^nC_p)$ é dado por $2^n$.
