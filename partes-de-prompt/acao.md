# Ação
*(Básico)*

***O que você espera que o Agente de Inteligência Artificial (Agente) faça, o que ele deve realizar.***

[<img src="../imagens/cards/006.png" width="375" height="375" align="left">](acao.md)

Essa é a única parte do proMpt que é certo que ninguem esquece, é literalmente o pedido que deseja fazer, o que você quer que a Inteligência Artifical (IA) faça especificamente.
```
Como um chefe de cozinha pode me explicar o que é um Ovo pochê?
```
```
Como um professor de culinária pode me explicar o que é um Ovo pochê?
```
Acima, por exemplo, tenho dois pedidos diferentes e os dois envolvem a mesma Ação ("me explicar o que é um Ovo pochê") todavia ela é uma ação má escrita, ou pouco específica.

O componente "Ação" está presente em várias "receitas" de proMpt, como a PACIF e a PACEF, incluive na PREP, mas com o nome de "Instrução Explicita" que é um nome muito bom, pois deixa claro que você precisa "deixar claro" o que realmente deseja que a IA faça.

Nos dois proMpts acima, mesmo determinando Papeis diferentes é bastante provável que eu não tenha resultados tão distintos quanto esperado, pois a ação solicitada, além de ser a mesma, tem poucos detalhes.

Poderiamos melhorar.
```
Como um chefe de cozinha descreva para o cardápio o que é um Ovo pochê?
```

Aqui a ação mudou completamente a intencionalidade, veja um outro teste.
```
Como um professor de culinária explique para um aluno iniciante o que é um Ovo pochê?
```

Tenho certeza que agora esses dois proMpts, mesmo se testados no mesmo Agente, devem trazer resultados completamente diferentes, pois fomos muito mais explicitos em nossos pedidos. Declaramos claramente o que desejamos que a IA produza.

Por isso, embora a Ação seja o mais obvio dos elementos que podem compor um proMpt, sua importancia não é reduzida e sua escrita não deve de forma alguma ser menosprezada. Aqui, mais do que nunca, é necessário lembrar-se de ser o mais específico possível, delimitando assim como o Agente deve proceder.

Se você fosse explicar para uma pessoa, esse nível de detalhe é importante também, pense, se perguntar a alguem "O que é um Ovo pochê" você terá uma resposta, por outro lado, se perguntas "Como você descreveria um Ovo pochê para um livro de receitas" certamente a resposta será outra, independente da pessoa. O mesmo vale para as IAs.

## Relações
<table>
<tr>
  <th>Componente</th>	<th>Método</th>	<th>Descrição</th>
</tr>
<tr>
  <td>Ação</td><td>PACIF</td><td>	Descrição explicita e específica do que deve ser feito.</td>
</tr>
  <tr>
  <td>Ação</td><td>PACEF</td><td>	Descrição explicita e específica do que deve ser feito.</td>
</tr>
<tr>
  <td>Explicit Instruction</td><td>PREP</td><td> Descrição explicita e específica do que deve ser feito.</td>
</tr>
</table>

## Referências
Agilers. Almoce e Aprenda: IA na Gestão e Liderança. Disponível em: https://miro.com/app/board/uXjVK8HHzF0=/?moveToWidget=3458764593995821713&cot=14. Acesso em: 15 ago. 2024.
<hr><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://davifma.github.io/proMpto/">prompto.github.io</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="http://linkedin.com/in/davifma">Davi Fontebasso Marques de Almeida</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""> <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>
