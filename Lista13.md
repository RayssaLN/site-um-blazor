Desenvolvimento Web

Usabilidade, Dev. Web, Mobile e Jogos

Professor Daniel Henrique Matos de Paiva

## Lista de Exercícios

## Esta lista de exercício deve:

- \- Ser realizada em equipes de até 05 alunos.

- \- Ser entregue no prazo proposto.

- \- Ter os algoritmos pedidos escritos em linguagem .NET.

- \- Ter todos os algoritmos devidamente indentados.

## Exercícios:

Crie um novo projeto chamado: SiteUmBlazor

Crie um novo repositório no github: site-um-blazor

Exercício 1: Criando a Página "Sobre Mim" (Foco: @page)

Objetivo: Compreender como transformar um componente Blazor em uma página navegável através do roteamento.

## Instruções:

- 1. Dentro da pasta Pages (ou Components/Pages) do seu projeto Blazor, crie um novo arquivo chamado Sobre.razor.

- 2. Adicione a diretiva de rota no topo do arquivo para que a página possa ser acessada pela URL /sobre.

- 3. Adicione elementos HTML simples para exibir:

- o Um título <h1> com o seu nome completo.

- o Um parágrafo <p> com uma breve descrição sobre o seu curso e o que você gosta de estudar.

- 4. Rode a aplicação (dotnet watch ou F5) e acesse no navegador http://localhost:XXXX/sobre para testar.


Desenvolvimento Web

Usabilidade, Dev. Web, Mobile e Jogos

Professor Daniel Henrique Matos de Paiva

Exercício 2: Contador de Clicks Simples (Foco: @code e @onclick)

Objetivo: Integrar lógica C# com a interface gráfica utilizando eventos de clique.

## Instruções:

- 1. Crie um novo arquivo chamado Contador.razor com a rota @page "/contador".

- 2. Na seção de marcação HTML:

- o Crie um título <h1> exibindo o valor atual de uma variável: Número de cliques: X.

- o Crie um botão <button> com o texto "Clique Aqui".

- 3. Na seção @code:

- o Declare uma variável inteira privada chamada quantidade iniciada em 0.

- o Crie um método C# chamado Incrementar que adicione 1 à variável quantidade.

- 4. Conecte o evento @onclick do botão ao método Incrementar.

- 5. Teste a aplicação e verifique se o número na tela é atualizado a cada clique.

## Exercício 3: Alternador de Mensagem (Foco: Estado Booleano e Interatividade)

Objetivo: Manipular a visibilidade de elementos no DOM utilizando variáveis de estado no Blazor.

## Instruções:

- 1. Crie um arquivo chamado Mensagem.razor com a rota @page "/mensagem".

- 2. Na seção @code:

- o Declare uma variável booleana privada chamada exibirMensagem com valor inicial false.


Usabilidade, Dev. Web, Mobile e Jogos

Professor Daniel Henrique Matos de Paiva

- o Crie um método chamado AlternarVisibilidade que inverta o valor da variável (de true para false e vice-versa).

## 3. Na estrutura HTML:

- o Crie um botão com o evento @onclick chamando o método AlternarVisibilidade.

- o O texto do botão deve mudar dinamicamente: se exibirMensagem for true, mostre "Ocultar Mensagem"; caso contrário, mostre "Exibir Mensagem".

- o Use uma estrutura condicional C# (@if) no HTML para exibir um parágrafo <p> com a mensagem "Bem-vindo ao desenvolvimento web com .NET 10!" somente quando exibirMensagem for true.

## Exercício 4: Placar Interativo (Desafio Integrador)

Objetivo: Utilizar múltiplos eventos de clique para alterar um mesmo estado de forma dinâmica.

## Instruções:

- 1. Crie um arquivo chamado Placar.razor com a rota @page "/placar".

- 2. Crie uma interface visual simples para um placar de jogo:

- o Exiba o valor de uma variável pontos (iniciando em 0).

- o Adicione três botões:

- Botão 1: "Somar 1 Ponto"

- Botão 2: "Subtrair 1 Ponto"

- Botão 3: "Zerar Placar"

- 3. Na seção @code:

- o Implemente os métodos correspondentes para somar 1, subtrair 1 e reiniciar a pontuação para 0.

- o Regra extra: No método de subtrair, garanta que o placar nunca fique negativo (se for menor que 0, mantenha em 0).

- 4. Vinculador os botões aos seus respetivos métodos via @onclick.


Desenvolvimento Web

Usabilidade, Dev. Web, Mobile e Jogos

Professor Daniel Henrique Matos de Paiva

## Guia Rápido de Sintaxe para Consulta

Razor CSHTML

@* 1. Roteamento *@

@page "/minha-rota"

<h3>Minha Página</h3>

@* 2. Evento de Clique *@

<button @onclick="ExecutarAcao">Clique me</button>

@* 3. Lógica C# *@

@code {

private int meuValor = 0;

private void ExecutarAcao()

{

meuValor++;

}

}

Ao concluir a atividade, suba seu projeto para o repositório no GitHub.
