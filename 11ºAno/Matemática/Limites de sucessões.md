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

### Operações algébricas
Sendo $(u_n)$ e $(v_n)$ sucessões [[#Limite de uma sucessão convergente|convergentes]], sendo, respetivamente, $\lim u_n = a$ e $\lim v_n=b$:
- ##### Soma
	$\lim (u_n+v_n)=\lim u_n + \lim v_n = a+b$
- ##### Multiplicação
	$\lim (u_n \times v_n)=\lim u_n \times \lim v_n = a \times b$
- ##### Divisão
	$\lim \frac u_n v_n = \f