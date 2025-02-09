## Conetivas proposicionais
Uma conetiva proposicional é uma **palavra ou expressão** cujo uso **permite formar novas proposições**
>[!Note] Exemplos de conetivas proposicionais
>- não
>- e
>- ou
>- ou... ou
>- se... então
>- se e só se
## Proposições simples e complexas/compostas
>[!Example] Proposições simples e complexas/compostas
>#### Proposições simples
>Não é usada **nenhuma conetiva proposicional**
>>Ex: O José é cantor.
>
>#### Proposições complexas/compostas
>É usada **uma ou mais conetivas proposicionais**
>> Ex: O José é cantor **e** dançarino

# Tipos de Proposições
## Negação
>[!Quote] Exemplo
>- A Maria **não** gosta de lógica.
>
>P: A Maria gosta de lógica
>>[!Tip] Nota
>>Esta ceninha do
>>*"P: blá blá
>>Q: blá blá blá"*
>>é o dicionário
>
>#### $\lnot$P
## Conjunção
>[!Quote] Exemplo
>- As vacas são mamíferos **e** seres vivos.
>
>P: As vacas são mamíferos
>Q: As vacas são seres vivos
>
>#### P $\land$ Q

| P | Q | P $\land$ Q |
| ---- | ---- | ---- |
| V | V | **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **F** |
^ Tabela da verdade da conjunção ^
A proposição é **verdadeira** quando **todas** as proposições componentes **são verdadeiras**.
## Disjunção inclusiva
>[!Quote] Exemplo
>- Vou a Paris **ou** vou a Londres.
>
>P: Vou a Paris
>Q: Vou a Londres
>
>#### P $\lor$ Q

| P | Q | P $\lor$ Q |
| ---- | ---- | ---- |
| V | V | **V** |
| V | F | **V** |
| F | V | **V** |
| F | F | **F** |
^ Tabela da verdade da disjunção inclusiva ^
A proposição é **verdadeira** quando **pelo menos uma** das proposições componentes **é verdadeira**.
## Disjunção exclusiva
>[!Quote] Exemplo
>- **Ou** vou a Paris **ou** vou a Londres.
>
>P: Vou a Paris
>Q: Vou a Londres
>
>#### P $\dot \lor$ Q

| P | Q | P $\dot \lor$ Q |
| ---- | ---- | ---- |
| V | V | **F** |
| V | F | **V** |
| F | V | **V** |
| F | F | **F** |
^ Tabela da verdade da disjunção exclusiva ^
A proposição é **verdadeira** quando as proposições componentes **têm valores de verdade opostos** (1 V e 1 F).

## Condicional
>[!Quote] Exemplo
>- **Se** ganhar o Euromilhões vou a Londres.
>
>P: Ganhar o Euromilhões
>Q: Vou a Londres
>
>#### P $\rightarrow$ Q

| P | Q | P $\rightarrow$ Q |
| ---- | ---- | ---- |
| V | V | **V** |
| V | F | **F** |
| F | V | **V** |
| F | F | **V** |
^ Tabela da verdade da proposição condicional ^
A proposição é **falsa** quando **o antecedente é verdadeiro e o consequente é falso**.

Antecedente: proposição do lado esquerdo (P neste caso)
Consequente: proposição do lado direito (Q neste caso)

## Bicondicional
>[!Quote] Exemplo
>- Vou a Paris **se e só se** ganhar o Euromilhões
>
>P: Vou a Paris
>Q: Ganhar o Euromilhões
>
>#### P $\leftrightarrow$ Q

| P | Q | P $\leftrightarrow$ Q |
| ---- | ---- | ---- |
| V | V | **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **V** |
^ Tabela da verdade da proposição condicional ^
A proposição é **verdadeira** quando as proposições componentes **têm valor de verdade igual**.

>[!Tip] Nota
>Aparentemente, é possível disjunções exclusivas com apenas um "ou" e disjunções inclusivas com 2 "ou". Por esta razão, para distinguir estes tipos de disjunções deve-se verificar se as disjuntas podem ser verdadeiras ao mesmo tempo ou não.
>
>Ou seja,
>- Podem ser verdadeiras ao mesmo tempo = **disjunção inclusiva**
>- Não podem ser verdadeiras ao mesmo tempo = **disjunção exclusiva**
## Proposições com várias conetivas
Numa mesma proposição composta podem existir várias conetivas.

Em alguns casos é necessário o uso de parênteses. (pág. 48 do livro *Dúvida Metódica*)
>[!Quote] Exemplo
>- Se dizes mentiras, então as pessoas não confiam em ti e afastam-se de ti
>
>P: Dizes mentiras.
>Q: As pessoas confiam em ti.
>R: As pessoas afastam-se de ti.
>
>#### P $\rightarrow$ ($\lnot$ Q $\land$ R)

Para saber se estas proposições são verdadeiras, tem de se fazer tabelas de verdade também, da mais simples para a proposição componente mais complexa. (pág. 56 do livro *Dúvida Metódica*)
>[!Tip] Nota
>Não dá para explicar tãoo bem por aqui, então deves fazer exercícios ou ler o livro, Dinis ;)

- **Tautologia**: Lei lógica/Argumento válido (a proposição é verdadeira em qualquer circunstância)
- **Contingente** (Há circunstâncias em que a proposição é verdadeira e outras que é falsa)
- **Contradição** (Proposição falsa em qualquer circunstância)
## Formas de inferência válida - Leis de Morgan
- A **negação de uma conjunção** é equivalente à **negação de cada uma das proposições de uma disjunção inclusiva**
- A **negação de uma disjunção inclusiva** é equivalente à **negação de cada uma das proposições de uma conjunção**
>[!Tip] Nota - se me esquecer das Leis de Morgan
>Para verificar se duas proposições são equivalentes, deve-se fazer a tabela da verdade com a bicondicionalidade das duas proposições.
>Se der uma tautologia (a proposição ser verdadeira em qualquer circunstância), então as proposições são equivalentes. Se nem sempre for verdadeira, então não são equivalentes.

