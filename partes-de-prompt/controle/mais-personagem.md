# +Personagem
*(Controle)*

***Qual personagem, real ou fictício, a Ineligência Artificial (IA) deve "fingir" ser ao realizar a criação?***

<img src="../../imagens/cards/021.png"  width="375" height="375" align="left">

Ao definir uma persona, um [Papel](../../partes-de-prompt/papel.md), para a IA assumir durante suas produções, seja apenas em um proMpt ou na criação/treinamento de um Agente de IA (Agente), você pode pedir que ela simule especificamente o comportamento de uma pessoa conhecida ou de uma personagem fictícia. Isso pode impactar em todos os tipos de proMpt.

Em criações pessoas e personagens impactam diretamente no estilo que será utilizado para realizá-las, enquanto para um [Conselheiro](../../tipos-de-prompt/conselheiro.md) pessoas diferentes terão pontos de vista e tons diferentes e, até, para tarefas simples essa escolha pode ter um impacto considerável.

Vamos ver como seria com um conselheiro no proMpt abaixo, por exemplo.

```
Como um professor de culinária crie um roteiro de até 50 minutos para explicar para um aluno iniciante em uma aula em grupo com diferentes níveis de conhecimento o que é um Ovo pochê?

Escreva seguindo o Exemplo de roteiro:

Introdução (Informme o tempo)
Conceitos envolvidos

Ação (Informe do Tempo)

Mise en place  (Informe do Tempo)
Informação de como os alunos devem preparar o ambiente antes de preparar o prato.

Execução  (Informe do Tempo)
Informação sobre como prepapar o prato.

Empratamento  (Informe do Tempo)
Informação sobre como os alunos devem apresentar o prato

Reflexão  (Informe do Tempo)
Atividade que leve os alunos a refletir sobre a realização do prato.

Ação  (Informe do Tempo)
Uma variação da receita anterior que permita aos alunos experimentarem o que aprenderam nela.

```

Em vez da apenas um professor de culinária e se eu pedisse isso para um jurado do Master Chefe?

```
Como se fosse a Paola Carosella atuando como professora de culinária crie um roteiro de até 50 minutos para explicar para um aluno iniciante em uma aula em grupo com diferentes níveis de conhecimento o que é um Ovo pochê?

Escreva seguindo o Exemplo de roteiro:

Introdução (Informme o tempo)
Conceitos envolvidos

Ação (Informe do Tempo)

Mise en place  (Informe do Tempo)
Informação de como os alunos devem preparar o ambiente antes de preparar o prato.

Execução  (Informe do Tempo)
Informação sobre como prepapar o prato.

Empratamento  (Informe do Tempo)
Informação sobre como os alunos devem apresentar o prato

Reflexão  (Informe do Tempo)
Atividade que leve os alunos a refletir sobre a realização do prato.

Ação  (Informe do Tempo)
Uma variação da receita anterior que permita aos alunos experimentarem o que aprenderam nela.

```

Agora reescreva o mesmo proMpt mas mude a Personagem, pode ser o Chef Gordon Ramsay, por exemplo, e provavelmente a receita continuará a mesma mas haverá uma mudança no tom da escrita.

Em proMpts [Ciativos](../../tipos-de-prompt/criativo.md) essa diferença também será notada, isso por que você está sendo mais específico, quando pedimos a uma IA que ela simule o comportamento de alguém, ela baseará suas criações e resultados nas criações e resultados que conhece dessa pessoa, ou seja, estamos limitando a sua busca.

Assim, eu posso solicitar que uma IA crie uma imagem como uma pessoa qualquer, como abaixo.

```
Crie uma imagem de um empresário com um deck do card game de "proMpto" nas mãos e atrás dele temos mais três agentes de inteligência artificial o empresario está satisfeito e confiante demonstrando controle sob os agentes que o acompanham, use um estilo retrofuturista, eles estão no alto do Corcovado no Rio de Janeiro, em 2024 às 00:01 do dia 1 de janeiro o foco principal da foto deve ser o verso do Deck com o logo "proMpto". A foto deve ter no tamanho 54x86mm. A camera usada é uma Câmera Instantânea com uma lente grande angular.
```

Mas também podemos pensar em uma personagem, um artista plastico conhecido e tentar simular as características de seu trabalho.

```
Como se você fosse o Eduardo Kobra crie uma imagem de um empresário com um deck do card game de "proMpto" nas mãos e atrás dele temos mais três agentes de inteligência artificial o empresario está satisfeito e confiante demonstrando controle sob os agentes que o acompanham, use um estilo retrofuturista, eles estão no alto do Corcovado no Rio de Janeiro, em 2024 às 00:01 do dia 1 de janeiro o foco principal da foto deve ser o verso do Deck com o logo "proMpto". A foto deve ter no tamanho 54x86mm. A camera usada é uma Câmera Instantânea com uma lente grande angular.
```

Você terá um resultado completamente diferente.

![image](https://github.com/user-attachments/assets/350aa6b0-4be9-4750-ade2-6e4e39922597)

Nesse caso a únida adição foi realmente um pedido para que a IA agisse como se fosse uma Personagem, pessoa específica.

[<img src="../../imagens/cards/003.png" width="187" height="187">](../../tipos-de-prompt/criativo.md)

[<img src="../../imagens/cards/005.png"  width="187" height="187">](../../partes-de-prompt/papel.md)<img src="../../imagens/cards/021.png"  width="187" height="187" align="left"> **Como se você fosse o Eduardo Kobra**

[<img src="../../imagens/cards/006.png"  width="187" height="187">](../../partes-de-prompt/acao.md) **crie uma foto de um empresário com um deck do card game de "proMpto" nas mãos e atrás dele temos mais três agentes de inteligência artificial**

[<img src="../../imagens/cards/011.png"  width="187" height="187">](../../partes-de-prompt/criacao/assunto.md)[<img src="../../imagens/cards/019.png"  width="187" height="187">](../../partes-de-prompt/criacao/mais-atuacao.md)<img src="../../imagens/cards/020.png"  width="187" height="187"> o empresario está satisfeito e confiante demonstrando controle sob os agentes de inteligência artificial que o acompanham, ***use um estilo retrofuturista***

[<img src="../../imagens/cards/007.png"  width="187" height="187">](../../partes-de-prompt/contexto.md)[<img src="../../imagens/cards/017.png"  width="187" height="187">](../../partes-de-prompt/criacao/mais-lugar.md)[<img src="../../imagens/cards/018.png"  width="187" height="187">](../../partes-de-prompt/criacao/mais-hora.md) **eles estão no alto do Corcovado no Rio de Janeiro, em 2024 às 00:01 do dia 1 de janeiro o foco principal da foto deve ser o verso do Deck com o logo "proMpto"**

[<img src="../../imagens/cards/008.png"  width="187" height="187">](../../partes-de-prompt/controle/formato.md) **A foto deve ter no tamanho 54x86mm.**

[<img src="../../imagens/cards/012.png"  width="187" height="187">](../../partes-de-prompt/criacao/equipamento.md) **A camera usada é uma Câmera Instantânea com uma lente grande angular.**

![img-zZO7G1nZWzH7wRs6tUVo5Ghr](https://github.com/user-attachments/assets/5566d9c4-cd93-45e9-b4b3-3058f39a2464)


## Relações
<table>
<tr>
  <th>Componente</th>	<th>Método</th>	<th>Descrição</th>
</tr>
<tr>
  <td>&lt;figure&gt;</td><td>HTML5</td><td>	usado para anotar ilustrações, diagramas, fotos, listagens de códigos, etc.</td>
</tr>  
</table>

## Referências
WORLD WIDE WEB CONSORTIUM (W3C). HTML5: Edition for Web Authors. The figure element. 09 ago. 2011. Disponível em: https://www.w3.org/TR/2011/WD-html5-author-20110809/the-figure-element.html. Acesso em: 04 set. 2024.

<hr><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://davifma.github.io/proMpto/">prompto.github.io</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="http://linkedin.com/in/davifma">Davi Fontebasso Marques de Almeida</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""> <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>
