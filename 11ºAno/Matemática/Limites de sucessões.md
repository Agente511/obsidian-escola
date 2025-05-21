## Limites de sucessões
### Limite de uma sucessão convergente
Uma sucessão **convergente** ($u_n$) admite um **único limite real** que se representa por $\lim_{x \to 2} u_n$, por $\lim_n u_n$ ou por $\lim u_n$.

- Todas as sucessões convergentes são **limitadas**.
- Todas as **sucessões monótonas** e **limitadas** são convergentes:
	- Uma sucessão **crescente em sentido lato** e **majorada** é **convergente**.
	- Uma sucessão **decrescente em sentido lato** e **minorada** é **convergente**.
- Existem sucessões não monótonas convergentes

### Limite de uma sucessão divergente
Uma sucessão **divergente** tende para **$+\infty$** ou **$-\infty$**.

- As sucessões divergentes **não são limitadas**.
- $u_n \rightarrow -\infty \iff -u_n \rightarrow +\infty$

### Limite de uma sucessão constante
O limite de uma sucessão constante é **igual à própria constante**.
>[!Note] Exemplo
>$\lim 2 = 2$

>[!Info] Nota
>O limite da sucessão **não se altera pelo comportamento de um número finito de termos**.
>>[!note] Exemplo
>>![[Pasted image 20250521180623.png|400]]
>>$\lim u_n = +\infty$

## Determinação de limites
### Produto entre uma sucessão limitada e uma sucessão que tende para 0
O **produto** de uma **sucessão limitada** $(u_n)$ por uma **sucessão que tende para 0** $(v_n)$ é uma **sucessão que tende para 0** $(w_n)$:
$\lim w_n = \lim(u_n \times v_n)=0$

>[!Note] Exemplo
>$$\begin{flalign}& \lim \frac {\cos n} n = \lim \cos n \times \frac 1 n = 0 &\end{flalign}$$
>
>($-1\leq \cos n \leq 1$, logo, é limitada)
>($\lim \frac 1 n = 0$)

### Operações algébricas com limites
#### Operações com limites finitos
Sendo $(u_n)$ e $(v_n)$ sucessões [[#Limite de uma sucessão convergente|convergentes]], sendo, respetivamente, $\lim u_n = a$ e $\lim v_n=b$:
- ##### Soma
	$\lim (u_n+v_n)=\lim u_n + \lim v_n = a+b$
- ##### Multiplicação
	$\lim (u_n \times v_n)=\lim u_n \times \lim v_n = a \times b$
- ##### Divisão
	$\lim \frac {u_n} {v_n} = \frac {\lim u_n} {\lim v_n} = \frac a b \ \ \ \ (b\neq 0)$
- ##### Produto de uma constante
	$\lim (k\ u_n) = k\ \lim u_n =k\ a$     ($k$ constante)
- ##### Potência
	- $\lim (u_n)^p =(\lim u_n)^p=a^p, \ \ \ p \in \mathbb Q$
	- $\lim a_n$, $a \in \mathbb R^+$ \ $\{1\}$
		  - Se $a>1$, $\lim a^n=+\infty$
		  - Se $0<a<1$, $\lim a^n=0$
- ##### Raiz
	- $\lim \sqrt {u_n} = \sqrt {\lim u_n}$    se $\lim u_n \geq 0$
	- $\lim \sqrt[n] a =\lim a^{\frac 1 n}=1$

>[!Note] Exemplo
>1. $\lim u_n=2$, $\lim v_n=4$
>$$\begin{flalign}& \lim {\sqrt {\frac {v_n} {u_n}}} = \sqrt {\frac {\lim v_n} {\lim u_n}} = \sqrt {\frac 4 2} = \sqrt 2 &\end{flalign}$$
#### Operações com limites infinitos
- ##### Soma
	- $a + (+\infty)=+\infty$
	- $a+ (-\infty)=-\infty$
	- $(+\infty)+(+\infty)=+\infty$
	- $(-\infty)+(-\infty)=-\infty$
- ##### Multiplicação
	- Se $a>0$, $a\times (+\infty)=+\infty$
	- Se $a<0$, $a\times (+\infty)=-\infty$
	- $(+\infty)\times (+\infty)=+\infty$
	- $(-\infty) \times (+\infty)=-\infty$
- ##### Potência
	- Se $p>0$, $(+\infty)^p=+\infty$
	- Se $p \in \mathbb N$ e é ímpar, $(-\infty)^p=-\infty$
	- Se $p \in \mathbb N$ e é par, $(-\infty)^p=+\infty$
- ##### Divisão
	- $$\begin{flalign}& \frac a {+\infty}=0^+ &\end{flalign}$$
	- $$\begin{flalign}& \frac a {-\infty}=0^- &\end{flalign}$$
	- $$\begin{flalign}& \frac a {0^+}=+\infty &\end{flalign}$$
	- $$\begin{flalign}& \frac a {0^-}=-\infty &\end{flalign}$$
- ##### Polinómio
	Seja $P(x)$ um polinómio de grau superior ou igual a 1, na forma reduzida, tem-se que:
	- Se o **coeficiente** do **termo de maior grau** é **positivo** $\lim P(n)=+\infty$
	- Se o **coeficiente** do **termo de maior grau** é **negativo** $\lim P(n)=-\infty$


>[!Note] Exemplo
>1. $\lim u_n=a$, $\lim v_n=+\infty$
>$\lim (u_n+v_n)=\lim u_n + \lim v_n= a +(+\infty)=+ \infty$
>.
>2. $\lim u_n=-3$, $\lim v_n=+\infty$
>$\lim (u_n \times v_n)= \lim u_n \times \lim v_n = -3 \times (+\infty) = -\infty$
>.
>3. $\lim u_n = +\infty$, $\lim v_n=-\infty$
>$$\begin{flalign}& \lim (u_n+v_n) = \lim u_n + \lim v_n = +\infty +(+\infty) = \infty-\infty &\end{flalign}$$
>Indeterminação

## Indeterminações
- $\infty-\infty$
- $\infty \times 0$
- $\frac \infty \infty$
- $\frac 0 0$
### Levantamento da indeterminação
#### Indeterminações envolvendo expressões com polinómios
##### $(\infty- \infty)$
O **limite de um polinómio** é considerado igual ao **limite do termo de maior grau** desse polinómio:
$\lim$ polinómio $= \lim$ (termo de maior grau)
>[!Note] Exemplo
>1. $u_n=n^2+4n$, $v_n=1-n^3$
>
>$\lim (u_n+v_n)=$
>$=\lim u_n + \lim v_n=$
>$=(+\infty)^2+4(+\infty)+1-(+\infty)^3$
>$=+\infty-\infty$
>
>$\lim (u_n+v_n) \overset{\infty-\infty} = \lim (n^2+4n+1-n^3)=\lim (-n^3+n^2+4n+1)=\lim (-n^3)=-\infty$
##### $(\frac \infty \infty)$
Considera-se o **termo de maior grau** no **numerador** e **denominador**
Deve-se transformar as indeterminações para ficarem do tipo $\frac \infty \infty$.
>[!Note] Exemplo
>1. $u_n=n^3+4n$, $v_n=3n^2$
>$$\begin{flalign}& \lim{\frac {u_n} {v_n}} \lim{\frac {n^3+4n} {3n^2}} \overset{\frac \infty \infty}= \frac {\lim n^3} {\lim 3n^2} = \lim {\frac n 3} = \frac {+\infty} {3} = +\infty &\end{flalign}$$
##### $(\frac 0 0)$
**Transforma**-se numa indeterminação $(\frac \infty \infty)$.
>[!Note] Exemplo
>$$\begin{flalign}& \lim {\frac {\frac {n^2} {2+n^3}} {\frac {n+1} {n^2}}} \overset{\frac 0 0} = \lim{\frac {n^4} {2n+2+n^4+n^3}} \overset{\frac \infty \infty} = \lim{\frac {n^4} {n^4}} =\lim{1} = 1  &\end{flalign}$$
##### $(0 \times \infty)$
**Transforma**-se numa indeterminação $(\frac \infty \infty)$ ou ($\frac 0 0$).
>[!Note] Exemplo
>1. $$\begin{flalign}& \lim (3n^2\times \frac {1} {n^2+1}) \overset{\infty\times 0} = \lim {\frac {3n^2} {n^2+1}} \overset{\frac \infty \infty} = \lim {\frac {3n^2} {n^2} = \lim 3=3} &\end{flalign}$$
#### Indeterminações envolvendo expressões com radicais
Em expressões com radicais, deve-se multiplicar a expressão pelo **conjugado**.

> [!NOTE] Exemplo
>$\lim (\sqrt {2n+1} -n) \overset{\infty-\infty}=$
>$$\begin{flalign}& \overset{\infty-\infty}= \lim{\frac {(\sqrt{2n+1}-n)(\sqrt{2n+1}+n)} {\sqrt{2n+1}+n}} &\end{flalign} =$$
>$$\begin{flalign}& = \lim{\frac {(\sqrt{2n+1})^2 -n^2} {\sqrt{2n+1}+n}} \overset{\frac \infty \infty}= &\end{flalign} =$$
>$$\begin{flalign}& \overset{\frac \infty \infty}= \lim{\frac {2n+1 -n^2} {\sqrt{2n+1}+n}} &\end{flalign} =$$
>$$\begin{flalign}& = \lim {\frac {-n^2} {n^2/\frac {2n} {n^2} + \frac 1 {n^2}} +n} &\end{flalign}$$
