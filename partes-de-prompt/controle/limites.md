# Limites
*(Controle & Informação)*

***O que você não deseja que a Inteligência Artificial (IA) faça, ou forneça na resposta. Quais são os parâmetros negativos.***

 <img src="https://github.com/user-attachments/assets/c974ca78-55d1-4ca0-920f-9d19d684394f" align="left" width="375" height="375">

Principalmente para profissionais de áreas técnicas essa deve ser uma prática, ou, ao menos, um tipo de informação bem conhecida. Impor Litmites, ou definir coisas que você deseja que não apareçam na resposta, ou formas de resultado que não estão na sua expectativa irá ajudar a dar ainda mais acertividade nas respostas que conseguirá dos Agentes de IA (Agentes) que você usa.

Os Limites podem ser vistos como parâmetros, ou instruções, negativos. Em vez de dizer "faça isso", "me diga aquilo", diremos "não quero assim", "não inclua aquilo" e assim por diante. Vamos dizer ao Agente o que queremos que ele retire de sua resposta, ou nem inclua.

Perceba que aqui estamos criando um filtro negativo, um limitante, já podemos ter feito algo parecido ao incluir Ecolhas no próprio tipo de proMpt (ou Agente), mas aqui trabalharemos em um nível mais baixo, pensando nos itens que não desejamos nas suas respostas.

Vamos relembrar de quando pedimos para uma IA escrever um item para ser incluído em um cardápio.

```
Como um chefe de cozinha descreva o que é um Ovo pochê para um cardápio que será usado na inauguração de um restaurante de comida francesa e fusões modernas traga a resposta em um parágrafo único com os ingredientes listados no final?

Escreva seguindo o exemplo:
A feijoada é um prato típico da culinária brasileira que consiste num guisado de feijão preto com vários tipos de carne de porco e de boi. É servida com farofa, arroz branco, couve refogada e laranja fatiada.
Ingredientes principais:
* feijão-preto;
* paio;
* carne de porco
* carne de boi

```

Pode ser que eu deseje limitar algumas gestões, por exemplo o número de linhas que a descrição deve ter (uma dica, em minha experiência com IAs generativas, solicitando em português eu percebi que limitar o número de linhas funciona melhor do que parágrafos ou caracteres). 

```
Como um chefe de cozinha descreva o que é um Ovo pochê para um cardápio que será usado na inauguração de um restaurante de comida francesa e fusões modernas traga a resposta em um parágrafo único de até 2 linhas com os ingredientes listados no final?

Escreva seguindo o exemplo:
A feijoada é um prato típico da culinária brasileira que consiste num guisado de feijão preto com vários tipos de carne de porco e de boi. É servida com farofa, arroz branco, couve refogada e laranja fatiada.
Ingredientes principais:
* feijão-preto;
* paio;
* carne de porco
* carne de boi

```

Provavelmente após essa mínima alteração incluindo o limite "de até 2 linhas" você terá uma resposta menor e mais consisa.

Um outro exemplo.

```
Como um professor de culinária crie um roteiro para explicar para um aluno iniciante em uma aula em grupo com diferentes níveis de conhecimento o que é um Ovo pochê?

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

Suponha neste caso que você tem uma limitação de 50 minutos para essas aulas, esse poderia ser um limite importante.

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

Você terá um roteiro possívelmente mais adequado ao tempo solicitado, mas deve perceber que talvez seja inviável utilizálo. Lembre-se que você é o humano nessa equação, quando incluiu um limite de tempo a IA tentará atender a todas as suas solicitações, então, nesse caso, ela dividirá o tempo máximo entre as áreas sugeridas para o roteiro, o que não será necessáriamente realista. A IA, no final, não sabe cozinhar e não é factual. Assim cabe ao humano validar e ajustar essas informações.

## Relações
<table>
<tr>
  <th>Componente</th>	<th>Método</th>	<th>Descrição</th>
</tr>
<tr>
  <td>Parameters</td><td>PREP</td><td>	Parâmetros Explicitos sobre a solicitação.</td>
</tr>
</table>

## Referências
Agilers. Almoce e Aprenda: IA na Gestão e Liderança. Disponível em: https://miro.com/app/board/uXjVK8HHzF0=/?moveToWidget=3458764593995821713&cot=14. Acesso em: 15 ago. 2024.
