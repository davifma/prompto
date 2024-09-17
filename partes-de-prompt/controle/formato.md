# Formato
*(Controle & Criação)*

***Como, em qual formato, a Inteligência Artificial (IA) deve entregar o resultado da requisição?***

  <img src="https://github.com/user-attachments/assets/769152cf-b7af-48e3-b560-da6254f21670" align="left" width="637" height="375">

Mesmo que você já tenha um bom proMpt construído, com os elementos básicos bem definidos (Tipo, Ação, Contexto e Papel), talvez o resultado não seja exatamente o que estava esperando, para isso podemos adicionar elementos de controle, para garantir um resultado mais alinhado com as nossas expectativas.

Definir um Formato de resposta altera drasticamente, obviamente, a forma como a IA vai te entregar a informação gerada. Diria que hoje esses formatos são ilimitados, um código de programação, uma tabela, um desenho, um ilustração, um vídeo, etc...

Vamos pensar nessa duas requisições:
```
Como um chefe de cozinha descreva o que é um Ovo pochê para um cardápio que será usado na inauguração de um restaurante de comida francesa e fusões modernas?
```

```
Como um professor de culinária explique para um aluno iniciante em uma aula em grupo com diferentes níveis de conhecimento o que é um Ovo pochê?
```

Embora bem escritas, não definem como essa entrega deve acontecer, podemos melhorar isso nos preocupando com o formato.

```
Como um chefe de cozinha descreva o que é um Ovo pochê para um cardápio que será usado na inauguração de um restaurante de comida francesa e fusões modernas traga a resposta em um parágrafo único com os ingredientes listados no final?
```
Nesse primeiro caso a diferença será tênue, mas você com certeza notará emboa o formato continue sendo de texto definimos alguns limites e detalhes desejados, como o um único parágrafo e a lista de ingredientes.

Vamos ver outros exemplos:

```
Como um professor de culinária crie um roteiro para explicar para um aluno iniciante em uma aula em grupo com diferentes níveis de conhecimento o que é um Ovo pochê?
```

Aqui, no lugar de uma simples explicação, teremos um roteiro de como essa explicação deveria acontecer durante uma aula. Agora vejamos outra variação:

```
Como um professor de culinária crie a receita escrita como passo a passo, igredientes e tabela nutricional para explicar para um aluno iniciante em uma aula em grupo com diferentes níveis de conhecimento o que é um Ovo pochê?
```

Nesse caso teremos uma receita mais detalhada e com os elementos solicitados.

De qualquer forma, lembre-se que mesmo sendo muito específico (o que é necessário) as IAs não são factuais, por tanto é sempre necessário se colocar no lugar de humano responsável da relação e verificar todas as informações geradas.

## Relações
<table>
<tr>
  <th>Componente</th>	<th>Método</th>	<th>Descrição</th>
</tr>
<tr>
  <td>Formato</td><td>PACIF</td><td>	Em qual formato de conteúdo a IA deve gerar  a resposta.</td>
</tr>
  <tr>
  <td>Formato</td><td>PACEF</td><td>	Em qual formato de conteúdo a IA deve gerar  a resposta.</td>
</tr>
</table>

## Referências
Agilers. Almoce e Aprenda: IA na Gestão e Liderança. Disponível em: https://miro.com/app/board/uXjVK8HHzF0=/?moveToWidget=3458764593995821713&cot=14. Acesso em: 15 ago. 2024.

