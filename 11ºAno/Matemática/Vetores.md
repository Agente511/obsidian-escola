## Produto escalar de vetores
Suponhamos fixada uma unidade de comprimento e sejam $\vec u$ e $\vec v$ **2 vetores não nulos**.
Consideremos:
- $O$ um **ponto fixo** qualquer;
- $P$, tal que $\vec {OP}=\vec u \ \ \ \ \ \ (P=O+\vec u$)
- $Q$, tal que $\vec {OQ} = \vec v \ \ \ \ \ \ (Q=O+\vec v$) 
- $Q'$ a **projeção ortogonal** de $Q$ na reta $OP$.

O produto escalar dos vetores $\vec u$ e $\vec v$ representa-se por $\vec u \cdot \vec v$ e é igual a:
- $\overline {OP} \times \overline {OQ'}$, se os vetores tiverem o **mesmo sentido**
  ![[Pasted image 20250129195237.png|200]]
- $-\overline {OP} \times \overline {OQ'}$, se os vetores tiverem **sentidos opostos**
  ![[Pasted image 20250129195248.png|200]]

Se **um dos vetores** **for nulo**, o **produto escalar é zero**.
![[Pasted image 20250129195256.png|200]]
### Ângulos de vetores
O **ângulo $\alpha$ de 2 vetores não nulos**, $\vec u$ e $\vec v$, é um ângulo convexo, nulo ou raso (nunca côncavo) definido por **representantes de cada um dos vetores com a mesma origem** (deve-se mover os vetores para terem a mesma origem).

A sua **amplitude** representa-se por **$(\vec u$^$\vec v)$**.

> [!Example] Propriedades do ângulo de vetores
> - Não é um ângulo orientado, logo $(\vec u$^$\vec v)=(\vec v$^$\vec u)$
> - A amplitude varia entre 0º e 180º (0 rad e $\pi$ rad)
> 	- 2 vetores colineares e com sentidos opostos formam um ângulo de 180º ($\pi$ rad)

>[!Summary] Cálculo do produto escalar a partir do ângulo de vetores
>$$\begin{flalign}& \vec u \cdot \vec v = ||\vec u|| \times ||\vec v|| \times \cos(\vec u ^\widehat{\ \ \ } \vec v) &\end{flalign}$$
### Sinal do produto escalar
O produto escalar de 2 vetores não nulos é um número real positivo, negativo ou nulo, **conforme $\cos(\vec u$^$\vec v)$ seja positivo, negativo ou nulo**, já que $||\vec u|| \times ||\vec v||$ é sempre positivo.

- ##### Positivo ($\vec u \cdot \vec v > 0$)
  $$\begin{flalign}& \cos(\vec u ^ⴷ \vec v) > 0 \iff 0º \leq (\vec u ^ⴷ \vec v) < 90º &\end{flalign}$$
- ##### Negativo ($\vec u \cdot \vec v < 0$)
  $$\begin{flalign}& \cos(\vec u ^ⴷ \vec v) < 0 \iff 90º < (\vec u ^ⴷ \vec v) \leq 180º &\end{flalign}$$
- ##### Nulo ($\vec u \cdot \vec v = 0$)
  $$\begin{flalign}& \cos(\vec u ^ⴷ \vec v) = 0 \iff (\vec u ^ⴷ \vec v) = 90º &\end{flalign}$$
#### Vetores perpendiculares
Dois vetores são **perpendiculares**, se o seu **produto escalar for nulo**.
$$\begin{flalign}& \vec u \cdot \vec v = 0 \iff \vec u \perp \vec v &\end{flalign}$$
### Propriedades do produto escalar
> [!Example] Propriedades do produto escalar
> - #### 1. (sem nome)
>   $$\begin{flalign}& \vec u \cdot \vec u = ||\vec u||^2 &\end{flalign}$$
> - #### 2. Propriedade comutativa
>   $$\begin{flalign}& \vec u \cdot \vec v = \vec v \cdot \vec u &\end{flalign}$$
> - #### 3. Propriedade associativa
>   $$\begin{flalign}& (\lambda\vec u)\cdot \vec v = \lambda (\vec u \cdot \vec v) \ \ \ \ \ \ \ \ \ \ \ (\lambda \in \mathbb R) &\end{flalign}$$
> - #### 4. Propriedade distributiva
>   $$\begin{flalign}& \vec w \cdot (\vec u + \vec v)=\vec w \cdot \vec u + \vec w \cdot \cdot \vec v &\end{flalign}$$
> 

### Produto escalar a partir das coordenadas de vetores
Fixado um referencial ortonormado $xOy$ no plano e sejam $\vec u(u_1, u_2)$ e $\vec v(v_1, v_2)$ dois vetores, então:
$$\begin{flalign}& \vec u \cdot \vec v = u_1 \times v_1 + u_2 \times v_2 &\end{flalign}$$

>[!Note] Exemplo
>1. Sendo $\vec u(-1, 4)$ e $\vec v(2, 3)$, determina o produto escalar $\vec u \cdot (2\vec v)$.
>
>	$$\begin{flalign}& \vec u \cdot (2\vec v) = 2(\vec u \cdot \vec v) = 2 \times (-1 \times 2 + 4 \times 3) = 2 \times 10 = 20 &\end{flalign}$$
>1. Sendo $A(-1, 3)$, $B(0, -1)$, $C(2, -3)$, [[#Ângulos de vetores|determina o ângulo]] $A\widehat BC$.
>
>	$A \widehat BC = (\vec {BA}\widehat{\ \ \ }\vec {BC})$
>	###### Determinação das coordenadas dos vetores
>	$\vec{BA}=A-B=$
>	$\ \ \ \ \ \ =(-1,3)-(0,-1)=$
>	$\ \ \ \ \ \ =(-1,4)$
>	
>	$\vec{BC}=C-B$
>	$\ \ \ \ \ \ =(2,-3)-(0,-1)$
>	$\ \ \ \ \ \ =(2,-2)$
>	###### Cálculo das normas dos vetores
>	$||\vec{BA}||=\sqrt{(-1)^2+4^2}=\sqrt{17}$
>	$||\vec{BC}||=\sqrt{2^2+(-2)^2}=\sqrt 8=2\sqrt 2$
>	###### Produto escalar e determinação da amplitude do ângulo de vetores
>	$\ \ \ \ \ \ \ \ \ \ \vec {BA} \cdot \vec {BC} = || \vec {BA} ||\ ||\vec {BC}|| \cos{(\vec {BA} \widehat{\ \ \ } \vec {BC})}$
>	$\iff (-1,4)\cdot(2,-2)=\sqrt{17}\times \sqrt{8} \cos (\vec {BA} \widehat{\ \ \ } \vec{BC})$
>	$\iff -2-8=\sqrt{136}\cos(\vec{BA}\widehat{\ \ \ }\vec{BC})$
>	$\iff -10=\sqrt{136}\cos(\vec{BA}\widehat{\ \ \ }\vec{BC})$
>	$\iff \cos(\vec{BA}\widehat{\ \ \ }\vec{BC})=-\frac {10} {\sqrt{136}}$
>	$\iff (\vec{BA}\widehat{\ \ \ }\vec{BC})=\cos^{-1}(-\frac{10}{\sqrt{136}})$
>	$\iff (\vec{BA}\widehat{\ \ \ }\vec{BC})=2,6$ rad

#### Vetores perpendiculares
Dado um vetor não nulo $\vec u(u_1,u_2)$, os vetores $\vec v(-u_2,u_1)$ e $\vec w(u_2,-u_1)$ (com as **coordenadas trocadas** e uma delas **simétrica**) são **perpendiculares a $\vec u$** e têm **igual norma** à de $\vec u$.

![[Pasted image 20250130002556.png|250]]
## Produto escalar no espaço
### Produto escalar a partir das coordenadas de vetores
Fixado um referencial ortonormado $Oxyz$ no plano e sejam $\vec u(u_1, u_2, u_3)$ e $\vec v(v_1, v_2, v_3)$ dois vetores, então:
$$\begin{flalign}& \vec u \cdot \vec v = u_1 \times v_1 + u_2 \times v_2 + u_3 \times v_3 &\end{flalign}$$
#### Vetores perpendiculares
Dado um vetor não nulo $\vec u(u_1,u_2,u_3)$, os vetores $\vec v(-u_2,u_1, 0)$ e $\vec w(u_3,0, -u_1)$, etc (com uma **coordenada nula**, as restantes **coordenadas trocadas** e uma delas **simétrica**) são **perpendiculares a $\vec u$** e têm **igual norma** à de $\vec u$.

## Relação entre declives de retas perpendiculares, no plano
Duas retas são **perpendiculares**, se o **produto dos seus declives for igual a $-1$**.

$$\begin{flalign}& m_r \times m_s = -1 \iff \vec u \perp \vec v &\end{flalign}$$
ou seja, $m_r=-\frac 1 {m_s}$

>[!Note] Exemplo
>1. Num referencial o.n. do plano, considera duas retas $r$ e $s$ de vetores diretores $\vec r(-5,2)$ e $\vec s(2,5)$, respetivamente. Verifica que as retas $r$ e $s$ são perpendiculares.
>	
>	$m_r=\frac 2 {-5} = -\frac 2 5$
>	$m_s=\frac 5 2$
>	
>	$m_r\times m_s=-\frac 2 5 \times \frac 5 2 = -1$
>	Logo, as retas $r$ e $s$ são perpendiculares.
