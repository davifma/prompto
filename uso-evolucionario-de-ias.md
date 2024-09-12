# Uso evolucionário de IAs
***Faça um uso intencional e evolucionário das IAs no seu dia a dia***

Evoluções, embora mais lentas, são menos dolorosas que as revoluções, inclusive, de acordo com o Método Kanban, são mais humanas também. Um dos princípios do Método Kanban é: "Acordar em buscar a melhoria através da mudança
evolucionária".

A ideia principal aqui é que você não mude a forma como faz as coisas da noite para o dia. Não é uma questão de "a partir de agora vamos usar Inteligencias Atificiais (IAs) para resolver isso", mas sim uma questão de "como nós podemos usar a IA para melhorar a forma como já realizamos as tarefas, fazendo-as com mais qualidade e em menos tempo" e esse é um processo evolucionário, que começa com o primeiro passo de simplesmente usar uma IA. 

Tudo deveria começar com uma reflexão sobre como uma IA pode me ajudar a resolver determinado problema e, a partir daí, saber então qual o tipo de Agente de IA (Agente) seria mais adequado. Essa reflexão pode ser individual, nesse caso muito natural e, até, quase imperceptível, porem vale pensar se eu necessito de um [Tarefeiro](tipos-de-prompt/tarefeiro.md), para em ajudar com tarefas simples e repetitivas, se seria mais indicado um [Conselheiro](tipos-de-prompt.md) que me indique caminhos e me de sugestões sobre determinado assunto ou um [Criativo](tipos-de-prompt.md) capaz de fazer as peças criativas que vou precisar para determinado trabalho.

Caso o uso da IA seja para uma equipe ou projeto que envolva mais pessoas, eu recomendo usar essa Inteligência Coletiva (muito mais poderosa que qualquer IA) e cocriar essa necessidade, una o grupo para fazer esse levantamento. Uma possível solução é o [Ai Planing Poker](tipos-de-prompt/cocriacao.md#ai-planing-poker) usando nosso [Deck de Consciência](README.md#deck-de-consciência).

Sabendo qual é a sua necessidade e qual é o [Tipo de proMpt ou Agente](tipos-de-prompt/README.md) que melhor deve atender a sua necessidade, então começa  mesmo o trabalho de uso das IAs.

Como em nosso exemplo: 

```
Quais são as tendências de moda para o outono?
```

Um pedido de ajuda simplista para um Agente [Conselheiro](tipos-de-prompt/conselheiro.md) é o start necessário para podermos evoluvionar. 

Nesse caso, só de nos lembrarmos do nosso [Deck de base](README.md#deck-de-base) já é possível termos uma enorme evolução.

```
Estou refazendo o meu guardaroupa e gostaria de ter um guarda roupa capsula com peças chaves para o uso diário como se você fosse um fashionista especialista em tendências para o dia a dia liste as principais tendências de moda masculina para o outono e de exemplos de cada uma delas.
```

[<img src="imagens/cards/3.png" width="187" height="318">](tipos-de-prompt/conselheiro.md)

[<img src="imagens/cards/8.png"  width="318" height="187">](partes-de-prompt/contexto.md) **Estou refazendo o meu guardaroupa e gostaria de ter um guarda roupa capsula com peças chaves para o uso diário**

[<img src="imagens/cards/6.png"  width="318" height="187">](partes-de-prompt/papel.md)**um fashionista especialista em tendências para o dia a dia**

[<img src="imagens/cards/7.png"  width="318" height="187">](partes-de-prompt/acao.md) **liste as principais tendências de moda masculina para o outono e de exemplos de cada uma delas**

Mesmo já tendo um resultado promissor com esse, ainda podemos melhorar, adequa-lo ainda mais.

```
Estou refazendo o meu guarda roupas e gostaria de ter um guarda roupas capsula com peças chaves para o uso diário como se você fosse um fashionista especialista em tendências para o dia a dia liste as principais tendências de moda masculina para o outono e de exemplos de cada uma delas, me mostre esse resultado em uma tabela em texto, fazendo um cruzamento entre as peças e as possíveis combinações, como no exemplo abaixo sugerindo apenas cinco peças chave no total.

                Tendencia 1       Tendencia 2   Tendencia 3    Explicação
Tendencia 1     Peça01+Peça02     PeçaN+PeçaN   Peça?+Peça?    Essas combinações são assim por que...
Tendencia 2     Peça01+Peça03     Peça?+Peça?   Peça?+Peça?    Essas combinações são assim por que...
Tendencia 3     Peça01+Peça04     Peça?+Peça?   Peça?+Peça?    Essas combinações são assim por que...
...             ...               ...           ...            ...
Tendencia N     Peça??+Peça??     Peça?+Peça?   Peça?+Peça?    Essas combinações são assim por que...
```

[<img src="imagens/cards/3.png" width="187" height="318">](tipos-de-prompt/conselheiro.md)

[<img src="imagens/cards/8.png"  width="318" height="187">](partes-de-prompt/contexto.md) **Estou refazendo o meu guardaroupa e gostaria de ter um guarda roupa capsula com peças chaves para o uso diário**

[<img src="imagens/cards/6.png"  width="318" height="187">](partes-de-prompt/papel.md)**um fashionista especialista em tendências para o dia a dia**

[<img src="imagens/cards/7.png"  width="318" height="187">](partes-de-prompt/acao.md) **liste as principais tendências de moda masculina para o outono e de exemplos de cada uma delas**

[<img src="imagens/cards/014.png"  width="318" height="187">](depois-do-prompt/ajuste-ou-continue.md#ajuste) [<img src="imagens/cards/9.png"  width="318" height="187">](partes-de-prompt/controle/formato.md)  **me mostre esse resultado em uma tabela em texto, fazendo um cruzamento entre as peças e as possíveis combinações**

<img src="imagens/cards/placeholder.png"  width="318" height="187"> [<img src="imagens/cards/10.png"  width="318" height="187">](partes-de-prompt/informacao/exemplos.md)  **como no exemplo abaixo (exemplo de tabela)**

<img src="imagens/cards/placeholder.png"  width="318" height="187"> [<img src="imagens/cards/11.png"  width="318" height="187">](partes-de-prompt/controle/limites.md)  **sugerindo apenas cinco peças chave no total**

Como falamos bastante, por termos feito um ajuste tornando o proMpt mais específico temos a tendência de uma resposta ainda mais adequada.

Talvez, para esse caso específico, você já esteja satisfeito com o resultado, que tal, então, [Continuar a conversa](depois-do-prompt/ajuste-ou-continue.md#continue-a-conversa), por exemplo (no mesmo chat):

```
Agora, realizando o mínimo de modificações possíveis nas peças, adeque esse guarda-roupas para o inverno.
```

[<img src="imagens/cards/3.png" width="187" height="318">](tipos-de-prompt/conselheiro.md)

[<img src="imagens/cards/8.png"  width="318" height="187">](partes-de-prompt/contexto.md) **Estou refazendo o meu guardaroupa e gostaria de ter um guarda roupa capsula com peças chaves para o uso diário**

[<img src="imagens/cards/6.png"  width="318" height="187">](partes-de-prompt/papel.md)**um fashionista especialista em tendências para o dia a dia**

[<img src="imagens/cards/7.png"  width="318" height="187">](partes-de-prompt/acao.md) **liste as principais tendências de moda masculina para o outono e de exemplos de cada uma delas**

[<img src="imagens/cards/014.png"  width="318" height="187">](depois-do-prompt/ajuste-ou-continue.md#ajuste) [<img src="imagens/cards/9.png"  width="318" height="187">](partes-de-prompt/controle/formato.md)  **me mostre esse resultado em uma tabela em texto, fazendo um cruzamento entre as peças e as possíveis combinações**

<img src="imagens/cards/placeholder.png"  width="318" height="187"> [<img src="imagens/cards/10.png"  width="318" height="187">](partes-de-prompt/informacao/exemplos.md)  **como no exemplo abaixo (exemplo de tabela)**

<img src="imagens/cards/placeholder.png"  width="318" height="187"> [<img src="imagens/cards/11.png"  width="318" height="187">](partes-de-prompt/controle/limites.md)  **sugerindo apenas cinco peças chave no total**

<img src="imagens/cards/placeholder.png"  width="318" height="187"> [<img src="imagens/cards/015.png"  width="318" height="187">](depois-do-prompt/ajuste-ou-continue.md#continue-a-conversa)

[<img src="imagens/cards/3.png" width="187" height="318">](tipos-de-prompt/conselheiro.md)

[<img src="imagens/cards/11.png"  width="318" height="187">](partes-de-prompt/controle/limites.md) **realizando o mínimo de modificações possíveis nas peças** 

[<img src="imagens/cards/7.png"  width="318" height="187">](partes-de-prompt/acao.md) **adeque esse guarda-roupas para o inverno**

Para realizar os testes acima, caso ainda não tenha um Agente [Conselheiro](tipos-de-prompt/conselheiro.md) de sua preferência, pode utilizar a [OratórIAfma](http://bit.ly/oratoriafma). Basta copiar e colar os proMpts sugeridos aqui para ver os resultados e sua evolução. 

## Referências
KANBAN University. The official Kanban guide. Disponível em: https://kanban.university/wp-content/uploads/2021/04/The-Official-Kanban-Guide_Portuguese_A4.pdf. Acesso em: 12 set. 2024.
