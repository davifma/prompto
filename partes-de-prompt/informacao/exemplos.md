# Exemplos
*(Informação)*

***Mostre para a Inteligência Artificial (IA) como você espera que seja o resultado***

 <img src="https://github.com/user-attachments/assets/b2edfb8e-9a4c-4cdc-a96b-064ece248255" align="left" width="637" height="375">

Embora as IAs possuam acesso a uma quantidade surreal de informações que, sozinhos, nós humanos não conseguiriamos aproveitar em sua totalidade, isso não garante que as informações que ela selecionará são as mais adequadas para a resposta que é esperada.

Uma amostra clara dessa questão é que muitos Agentes de IA (Agentes) já tem em sua programação uma rotina de solicitação de exemplos ou validação de respostas (para serem usadas como exemplos para novas respostas), como quando você corrigi uma IA generativa e ela te entrega mais de uma opção para a nova resposta, solicitando que você indique a melhor, ou IAs Criativas que te dão mais de uma opção de resultado (como imagens, vídeos e textos) e pedem que indique qual atendeu melhor a sua solicitação.

Aqui você está vendo na prática a IA aprendendo para te atender melhor.

Mas, principalmente, se você estiver com dificuldades para obter um resultado da foma como deseja da IA, mesmo tendo definido corretamente que tipo de Agente deveria usar, já criou um proMpt com Papel, Açção e Contextos bem definidos e, até incluiu o Formato desejado (o que supostamente garantiria uma entrega correta) e mesmo assim ainda não conseguiu exatamente o que desejava da IA. 

Uma possibilidade simples é mostrar ao Agente como você deseja o resultado, já na entrada do proMpt fornecer um ou mais "Exemplos" de como espera receber essa resposta.

```
Como um chefe de cozinha descreva o que é um Ovo pochê para um cardápio que será usado na inauguração de um restaurante de comida francesa e fusões modernas traga a resposta em um parágrafo único com os ingredientes listados no final?
```

No exemplo do cardápio pode ser que eu deseje a lista de igredientes feita de uma forma específica.

```
Como um chefe de cozinha descreva o que é um Ovo pochê para um cardápio que será usado na inauguração de um restaurante de comida francesa e fusões modernas traga a resposta em um parágrafo único com os ingredientes listados no final?

Por exemplo:
A feijoada é um prato típico da culinária brasileira que consiste num guisado de feijão preto com vários tipos de carne de porco e de boi. É servida com farofa, arroz branco, couve refogada e laranja fatiada.
Ingredientes principais:
* feijão-preto;
* paio;
* carne de porco
* carne de boi

```

Adicionando o exemplo de um texto no formato que deseja é mais provavel que a IA entregue de fato um resultado alinhado as suas expectativas, inclusive ajudando na padronização da informação.

```
Como um professor de culinária crie um roteiro para explicar para um aluno iniciante em uma aula em grupo com diferentes níveis de conhecimento o que é um Ovo pochê?
```

No caso acima, solicitamos um roteiro para ensinar um aluno em meio a uma turma, mas, um exemplo, poderia estruturar melhor essa solicitação.

```
Como um professor de culinária crie um roteiro para explicar para um aluno iniciante em uma aula em grupo com diferentes níveis de conhecimento o que é um Ovo pochê?

Exemplo de roteiro:

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

Outra possível vantagem de fornecer exemplos é buscar a padronização dos resultados, nesse caso, de uma escola de culinária, pode ser interessante que todos os roteiros de aula tenham um formato semelhante se vários professores forem usar o mesmo roteiro.

Outra possibilidade, o livro de receitas, nesse caso fornecer um exemplo também falitaria que todas as receitas tivessem o mesmo padrão visual por exemplo.

Fornecer mais informações, como Exemplos, para o Agente que estiver usando deve facilitar que sua entrega esteja mais adequada as espectativas. Vale lembrar que, mesmo assim, as IAs generativas não são factuais, por tanto, como humanos dentro do processo, devemos nos responsábilizar, conferir e validas as informações fornecidas por elas.

Como se estivessemos falando com um outro humano, dar Exemplos certamente facilitará e tornará essa comunicação mais simples. Não tenha dúvida. Sabe aquela frase "quer que eu desenhe"? Quando estiver lidando com IAs sempre suponha que ela quer.

## Relações
<table>
<tr>
  <th>Componente</th>	<th>Método</th>	<th>Descrição</th>
</tr>
<tr>
  <td>Exemplos</td><td>PACEF</td><td>	Forneça um exemplo de como deseja a resposta.</td>
</tr>
</table>

## Referências
Agilers. Almoce e Aprenda: IA na Gestão e Liderança. Disponível em: https://miro.com/app/board/uXjVK8HHzF0=/?moveToWidget=3458764593995821713&cot=14. Acesso em: 15 ago. 2024.


