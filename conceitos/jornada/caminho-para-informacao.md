# Caminho para informação

O **Caminho para Informação** é um dos grupos de elementos do Alpha (proMpto) e é composto pelas entidades  **[Exemplos](../../partes-de-prompt/informacao/exemplos.md)**, **[../../Limites](partes-de-prompt/controle/limites.md)** e **[../../Dados externos](partes-de-prompt/informacao/dados-externos.md)**. Este caminho se concentra em como fornecer informações adicionais e restrições para a Inteligência Artificial (IA) a fim de refinar os resultados obtidos.

[<img src="../../imagens/cards/009.png" width="187" height="187">](../../partes-de-prompt/informacao/exemplos.md)

[<img src="../../imagens/cards/010.png" width="187" height="187">](../../partes-de-prompt/controle/limites.md)

[<img src="../../imagens/cards/013.png" width="187" height="187">](../../partes-de-prompt/informacao/dados-externos.md)

**[Exemplos](../../partes-de-prompt/informacao/exemplos.md):** Fornecer **exemplos** ao Agente de IA (Agente) é uma maneira eficaz de mostrar como você espera que o resultado seja. Mesmo que as IAs tenham acesso a vastas quantidades de informações, isso não garante que elas selecionarão as mais adequadas para a sua necessidade.

- Ao dar um ou mais **[Exemplos](../../partes-de-prompt/informacao/exemplos.md)** diretamente no prompt, você demonstra ao Agente o formato e o conteúdo desejados. Isso é especialmente útil quando você está com dificuldades para obter o resultado esperado, mesmo tendo definido o tipo de Agente, o Papel, a Ação e o Contexto.
  - Por exemplo, ao solicitar um roteiro de aula, fornecer um **exemplo** da estrutura desejada (Introdução com tempo, Conceitos, Ação com tempo, etc.) torna mais provável que a IA entregue um resultado alinhado às suas expectativas e ajuda na padronização da informação.
  - Assim como explicar algo a outro ser humano, dar **[Exemplos](../../partes-de-prompt/informacao/exemplos.md)** facilita a comunicação com a IA, tornando suas expectativas mais claras. A ideia é que, ao lidar com IAs, você deve sempre supor que elas precisam de um "desenho" do que você quer.

**[Limites](../../partes-de-prompt/controle/limites.md):** Impor **[Limites](../../partes-de-prompt/controle/limites.md)** ou definir o que você não deseja que a IA inclua na resposta ajuda a direcionar ainda mais os resultados dos Agentes de IA. **[Limites](../../partes-de-prompt/controle/limites.md)** podem ser vistos como instruções negativas.

- Em vez de apenas dizer o que fazer, você informa o que não fazer ou o que não incluir. Isso cria um filtro negativo, especificando os itens que você quer que o Agente retire ou nem mesmo considere em sua resposta.
  - Por exemplo, ao solicitar a descrição de um prato para um cardápio, você pode limitar o número de linhas da descrição para torná-la mais concisa.
  - Da mesma forma, ao pedir a criação de um roteiro de aula, você pode definir um limite de tempo para a duração da aula. No entanto, é importante lembrar que a IA tentará atender a todas as solicitações, e o resultado pode não ser realista, sendo necessária a validação humana.

**[Dados externos](../../partes-de-prompt/informacao/dados-externos.md):** **[Dados externos](../../partes-de-prompt/informacao/dados-externos.md)** são informações necessárias ou complementares que não estão publicamente disponíveis para a IA. Frequentemente, esse recurso é utilizado com prompts do tipo Tarefeiro, quando se deseja que a IA manipule informações privadas, por exemplo.

- Para que a IA trabalhe com esses dados, é necessário fornecê-los, seja copiando e colando a informação no prompt ou, como é comum em muitos Agentes atuais, anexando arquivos.
  - Um exemplo prático é fornecer uma lista de participantes de um evento para calcular a média de idade. A IA não teria acesso a essa lista a menos que você a fornecesse diretamente.
 - A inclusão de **[Dados externos](../../partes-de-prompt/informacao/dados-externos.md)** se alinha com o Modelo GROW, especificamente com a necessidade de informações para avaliar a "Realidade" em que uma determinada ação será aplicada.
 - É crucial estar atento às políticas de privacidade e segurança do Agente de IA ao fornecer **[Dados externos](../../partes-de-prompt/informacao/dados-externos.md)**, investigando como essas informações são tratadas em relação a sigilo e conformidade com regulamentações como a LGPD. Além disso, mesmo com dados reais, a IA pode cometer erros, reforçando a importância da revisão humana.

Em resumo, o **Caminho para Informação** enfatiza a importância de enriquecer seus prompts com **[Exemplos](../../partes-de-prompt/informacao/exemplos.md)** do resultado desejado, definir **[Limites](../../partes-de-prompt/controle/limites.md)** para restringir a resposta da IA e fornecer **[Dados externos](../../partes-de-prompt/informacao/dados-externos.md)** quando a informação necessária não estiver publicamente acessível, tudo isso visando obter resultados mais precisos e alinhados às suas necessidades.

## Relações
- ### [Bússola de Implantação](../../direcoes/bussola.md) 
- ### Trilha Principal
- #### [Um mapa para infinitos proMpts](../../um-mapa-para-infinitos-prompts.md)
  - ##### [Completo ou complexo?](../../prompts-complexos.md) 
- #### Caminho da Produção
  - ##### [Caminho para controle](../../conceitos/jornada/caminho-para-controle.md)
      - [Limites](../../partes-de-prompt/controle/limites.md)
  - ##### Caminho para Informação
      - [Exemplos](../../partes-de-prompt/informacao/exemplos.md)
      - [Limites](../../partes-de-prompt/controle/limites.md)
      - [Dados externos](../../partes-de-prompt/informacao/dados-externos.md)

<hr>
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://davifma.github.io/proMpto/">prompto.github.io</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="http://linkedin.com/in/davifma">Davi Fontebasso Marques de Almeida</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""> <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>
