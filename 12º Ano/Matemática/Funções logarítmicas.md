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
- $a^{\log_a k} = k$, $k \in \mathbb R$
## Funções logarítmicas
A função definida por $f(x) = \log_a(x)$, em $\mathbb R^+$, com $a \in \mathbb R^+$\ $\{1\}$, designa-se por função logarítmica de base $a$ e representa-se por $\log_a$.

É a **função inversa da [[Juros compostos, Número de Neper e Funções exponenciais#Funções exponenciais|função exponencial]]**:
$a^x=y \iff x = \log_a(y) \iff f^{-1}(y) = \log_a(y)$

### Propriedades
##### Função logarítmica de base $a>1$
- **Domínio**: $\mathbb R^+$
- **Contradomínio**: $\mathbb R$
- **Variação**: crescente
- **Zeros**: $\{1\}$
- **Sinal**:
	- **Positiva** em $]1, +\infty[$, ou seja, $\log_a(x)>0 \iff x > 1$
	- **Negativa** em $]0, 1[$, ou seja, $\log_a(x)<0 \iff 0 < x < 1$
- **Injetiva**
- **Contínua**
- **Limites**:
	- $\underset{x \to +\infty} \lim \log_a(x) = +\infty$
	- $\underset{x \to 0^+} \lim \log_a(x)=-\infty$
- **Assíntotas**: $x=0$ é assíntota vertical ao gráfico da função.
##### Função logarítmica de base $0<a<1$
- **Domínio**: $\mathbb R^+$
- **Contradomínio**: $\mathbb R$
- **Variação**: decrescente
- **Zeros**: $\{1\}$
- **Sinal**:
	- **Positiva** em $]0, 1[$, ou seja, $\log_a(x)<0 \iff 0 < x < 1$
	- **Negativa** em $]1, +\infty[$, ou seja, $\log_a(x)>0 \iff x > 1$
- **Injetiva**
- **Contínua**
- **Limites**:
	- $\underset{x \to +\infty} \lim \log_a(x) = -\infty$
	- $\underset{x \to 0^+} \lim \log_a(x)=+\infty$
- **Assíntotas**: $x=0$ é assíntota vertical ao gráfico da função.

## Propriedades algébricas dos logaritmos
- $\log_a(x \times y) = \log_a(x)+\log_a(y)$
- $\log_a(\frac x y) = \log_a(x)-\log_a(y)$
- $\log_a(x^p)=p \times \log_a(x)$, $p\in \mathbb R$
	- $\log_a(\frac 1 x) = -\log_a(x)$
## Equações e inequações com logaritmos
## Derivada da função logarítmica

