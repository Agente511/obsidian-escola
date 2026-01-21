## Derivada de segunda ordem de uma função
Dada uma função real de variável real $f$, diferenciável num intervalo $I$, tal que a função derivada $f'$ é diferenciável num ponto $a \in I$, a derivada $(f')'(a)$ chama-se **segunda derivada** (ou derivada de segunda ordem) **de $f$ no ponto $a$**. 
Representa-se por **$f''(a)$**.

> [!Summary] Definição de segunda derivada de $f$ no ponto $a$
>Assim, se a função derivada $f'$ é diferenciável em $a$, entãõ:
>
>$\large f''(a) = \underset{x \rightarrow a} \lim \frac {f'(x)-f'(a)} {x-a}$

Quando existe $f''(a)$ em $a$, diz-se que **$f$ é duas vezes diferenciável** (ou duas vezes derivável) **em $a$**.
Uma função é **duas vezes diferenciável** se for **duas vezes diferenciável no domínio**.

>[!Tip] Nota
>Derivando novamente a segunda derivada, obter-se-ia a terceira derivada $f'''(x)$ e, assim, sucessivamente.

## Aplicação da noção de segunda derivada ao estudo de funções
>[!Summary] Teorema
>Seja $f$ uma função duas vezes diferenciável num intervalo $I = ]a, b[$
>- Se $f''(x)>0, \forall x \in ]a, b[$, então o **gráfico de $f$** tem a **concavidade voltada para cima** 
>  e $f'$ [[Derivadas de funções reais de variável real e aplicações#^19c1a2|é estritamente crescente]].
>- Se$f''(x)<0, \forall x \in ]a, b[$, então o **gráfico de $f$** tem a **concavidade voltada para baixo** 
>  e $f'$ [[Derivadas de funções reais de variável real e aplicações#^19c1a2|é estritamente decrescente]].
### Segunda derivada aplicada ao estudo do sentido das concavidade e dos pontos de inflexão
>[!Summary] Método para estudar o sentido das concavidades e os pontos de inflexão do gráfico de uma função $f$ duas vezes diferenciável
>1.  Determinar o **domínio** da função $f$.
>2. Calcular a **1.ª derivada** ($f'(x)$).
>3. Calcular a **2.ª derivada** ($f''(x)$).
>4. Determinar os **zeros da segunda derivada**, através da equação $f''(x)=0$.
>5. Construir um quadro que relacione o **sinal de f'' e os zeros da 2.ª derivada** com o **sentido das concavidades e os pontos de inflexão do gráfico da função**.
>	> [!NOTE] Exemplo
>	> | $x$ | $-\infty$  | $-2$ |  | $0$ |  | $2$ | $+\infty$  |
>	> | --- | ---| --- | --- | --- | --- | --- | --- |
>	> | $f''(x)$ | $-$ | N.D. | $+$ | 0 | $-$ | N.D. | $+$ |
>	> | $f(x)$  | $\cap$ | N.D. | $\cup$ | P.I. | $\cap$ | N.D. | $\cup$ |
>
>6. Escrever as **conclusões**.
>	>[!Note] Exemplo
>	>O gráfico da função $f$ tem a concavidade voltada para cima em $]-2, 0[$ e em $]2, +\infty[$ e a concavidade voltada para baixo em $]-\infty, -2[$ e em $]0, 2[$.
>	>
>	>Existe um ponto de inflexão em $x=0$.


