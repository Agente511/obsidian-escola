## Conceito de logaritmo
O logaritmo é o **expoente** a que é preciso elevar uma **base $a$** para **obter $x$**, representando-se por $\log_a(x)$.

>[!Summary] Logaritmo
>$\large \log_a (x) = y \iff x = a^y$
>
>Sendo:
>- $a \in \mathbb R^+$\ $\{1\}$
>- $x \in \mathbb R^+$  (pois não existe nenhuma potência que resulte em 0 ou em número negativo)
>  >[!Warning] Atenção
>**Expressões como $\log_a(0)$ e $\log_a(-1)$ não têm significado em $\mathbb R$**, visto não existir nenhum valor real $x$ tal que $a^x=0$ ou $a^x=-1$.

>[!Note] Exemplos
>- $2^x = 10 \iff x = \log_2 (10)$
>- $\log_2 x = 6 \iff x = 2^6$

>[!Info] Nota
>- **Logaritmo decimal**: $\log(x)= \log_{10} (x)$ 
>- **Logaritmo neperiano**: $\ln(x)= \log_e (x)$
### Propriedades
A partir da definição de logaritmo, tem-se que:
- $\log_a(a)=1$
- $\log_a(1)=0$
- $\log_a (a^k)=k$, $k \in \mathbb R$
- $a^{\large \log_a k} = k$, $k \in \mathbb R$
## Funções logarítmicas
A função definida por $f(x) = \log_a(x)$, em $\mathbb R^+$, com $a \in \mathbb R^+$\ $\{1\}$, designa-se por função logarítmica de base $a$ e representa-se por $\log_a$.

É a **função inversa da [[Juros compostos, Número de Neper e Funções exponenciais#Funções exponenciais|função exponencial]]**:
$a^x=y \iff x = \log_a(y) \iff f^{-1}(y) = \log_a(y)$

### Propriedades
- **Domínio**: $\mathbb R^+$
- **Contradomínio**: $\mathbb R$
- **Zeros**: $\{1\}$
- **Injetiva**
- **Contínua**
- **Assíntotas**: $x=0$ é assíntota vertical ao gráfico da função.

> [!Summary] Propriedades das funções logarítmicas de base $a > 1$
> ![[Pasted image 20260317235216.png|250]]
> 
> - **Variação**: crescente
> - **Sinal**:
> 	- **Positiva** em $]1, +\infty[$, ou seja, $\log_a(x)>0 \iff x > 1$
> 	- **Negativa** em $]0, 1[$, ou seja, $\log_a(x)<0 \iff 0 < x < 1$
> - **Limites**:
> 	- $\underset{x \to +\infty} \lim \log_a(x) = +\infty$
> 	- $\underset{x \to 0^+} \lim \log_a(x)=-\infty$

> [!Summary] Propriedades das funções logarítmicas de base $0<a<1$
> ![[Pasted image 20260318001033.png|250]]
> - **Variação**: decrescente
> - **Sinal**:
> 	- **Positiva** em $]0, 1[$, ou seja, $\log_a(x)<0 \iff 0 < x < 1$
> 	- **Negativa** em $]1, +\infty[$, ou seja, $\log_a(x)>0 \iff x > 1$
> - **Limites**:
> 	- $\underset{x \to +\infty} \lim \log_a(x) = -\infty$
> 	- $\underset{x \to 0^+} \lim \log_a(x)=+\infty$

#### Propriedades algébricas dos logaritmos
- **Multiplicação**: $\log_a(x \times y) = \log_a(x)+\log_a(y)$
- **Divisão**: $\log_a(\frac x y) = \log_a(x)-\log_a(y)$
- **Potência**: $\log_a(x^p)=p \times \log_a(x)$, $p\in \mathbb R$
	- Caso particular: $\log_a(\frac 1 x) = \log_a(x^{-1}) = -\log_a(x)$
	- >[!WARNING] PÔR AVISO DE QUE $\log (x^2) \neq 2\log(x)$, $\log (x^2) = 2\log(|x|)$.
		#todo
- **Mudança de base**: $\log_a(x) = \large \frac {\log_b(x)} {\log_b (a)}$
	>[!Note] Exemplo
	>$\log_2 5 = \large \frac {\ln 5} {\ln 2} = \large \frac {\log_7 5} {\log_7 2} = \large \frac {\log 5} {\log 2}$

- $a^x=e^{x \ln (a)}$
### Equações envolvendo logaritmos
- $\log_a (x)= \log_a(y)$
	$\iff x=y$, $\forall x,y \in \mathbb R^+$
- $\log_a(x)=y$
	$\iff x = a^y$

>[!Example] Resolução de equações envolvendo logaritmos
>1. Determinar o domínio da expressão.
>2. Caso haja logaritmos de bases diferentes, aplicar a regra da mudança de base e escrever todos os logaritmos na mesma base.
>3. Utilizar as propriedades operatórias dos logaritmos, com precaução, de forma a obter uma expressão do tipo $\log_a(x)=\log_a(y)$ ou $\log_a(x)=y$.
>4. Resolver a equação obtida.
>5. Apresentar o conjunto-solução, intersetando as soluções da equação com o domínio da expressão inicial.

### Inequações envolvendo logaritmos
- Se $a>1$, a função é **estritamente crescente**, logo $\log_a(x)<\log_a(y) \iff x<y$, $\forall x,y \in \mathbb R^+$ (**sinal mantém-se**)
- Se $0<a<1$, a função é **estritamente decrescente**, logo $\log_a(x) < \log_a(y) \iff x>y$, $\forall x,y \in \mathbb R^+$ (**sinal inverte**)

>[!Example] Resolução de inequações envolvendo logaritmos
>1. Determinar o domínio da expressão.
>2. Caso haja logaritmos de bases diferentes, aplicar a regra da mudança de base e escrever todos os logaritmos na mesma base.
>3. Utilizar as propriedades operatórias dos logaritmos, com precaução, de forma a obter uma expressão do tipo $\log_a(x)>\log_a(y)$ ou $\log_a(x)>y$ (ou com sinais $<$, $\geq$, $\leq$).
>4. Se $a>1$, mantém-se o sinal.
>   Se $0<a<1$, inverte-se o sinal.
>5. Resolver a inequação obtida.
>6. Apresentar o conjunto-solução, intersetando as soluções da equação com o domínio da expressão inicial.
### Derivada da função logarítmica
$\large (\ln u)'=\frac {u'} u$

$\large (\log_a u)' = \frac {u'} {u \times \ln a}$
