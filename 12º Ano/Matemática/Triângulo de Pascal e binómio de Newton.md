## Triângulo de Pascal
>[!Summary] Propriedades
>1. $^nC_p=^nC_{n-p}$
>2. $$\begin{flalign}& \sum_{p=0}^n\ ^nC_p = 2^n &\end{flalign}$$
>3. $^nC_p+^nC_{p+1}=^{n+1}C_{p+1}$

O triângulo de Pascal pode ser construído indefinidamente com recurso à última propriedade, isto é, somando dois números consecutivos de uma linha obtém-se o número colocado entre eles na linha seguinte.

![[Pasted image 20251012135839.png]]

Cada **elemento** que constitui o triângulo corresponde aos chamados **coeficientes binomiais**, $^nC_p$.
Calculando os respetivos valores dos coeficientes binomiais, o triângulo também pode ser representado da forma seguinte:

![[Pasted image 20251012135947.png]]

>[!Summary] Notas
>1. Cada **linha começa e acaba em 1**. $(^nC_0=^nC_n)$
>2. Em cada linha, **elementos igualmente afastados dos extremos** são **iguais**. $(^nC_p=^nC_{n-p})$
>3. Cada elemento, que **não esteja num dos extremos** de uma linha, é **igual à soma dos elementos que estão acima dele**, na **linha anterior**, um à **esquerda** e outro à **direita**. $(^nC_p+^nC_{p+1}=^{n+1}C_{p+1})$
>4. O **segundo e o penúltimo elementos** da linha de ordem $n$ são ambos **iguais a $n$**.
>5. A **soma de todos os elementos da linha** de ordem $n$ é **$2^n$**.
>6. A **linha** de ordem $n$ tem **$n+1$ elementos**.
>7. Se **$n$** é 
>	- **par**, a **linha** de ordem $n$ tem um **número ímpar de elementos**, sendo o **maior** deles o **elemento central**, que é $^nC_{\frac n 2}$
>	- b

