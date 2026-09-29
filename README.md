# SiteUmBlazor

Projeto desenvolvido em **Blazor WebAssembly (.NET 10)** referente aos exercícios propostos na **Lista 13** da disciplina de Usabilidade, Desenvolvimento Web, Mobile e Jogos (UDWMJ).

---

## 👨‍🎓 Informações do Aluno

- **Nome:** Rayssa Leal Nascimento
- **RA:** 12419301
- **Curso:** Engenharia de Software
- **Campus:** UniBH - Estoril
- **Professor:** Daniel Henrique Matos de Paiva

---

## 📌 O que foi proposto e desenvolvido

A atividade consiste na criação de um projeto em Blazor WebAssembly contendo 4 exercícios práticos para fixar conceitos de roteamento (`@page`), estado C# (`@code`), tratamento de eventos (`@onclick`) e renderização condicional (`@if`):

1. **Página "Sobre Mim" (`/sobre`)**
   - Apresentação do aluno com nome completo (`<h1>`) e breve descrição (`<p>`).

2. **Contador de Clicks (`/contador`)**
   - Página interativa com um botão que incrementa uma variável privada `quantidade` e exibe na tela o número atualizado de cliques.

3. **Alternador de Mensagem (`/mensagem`)**
   - Utilização de estado booleano (`exibirMensagem`) para alternar dinamicamente o texto do botão ("Exibir Mensagem" / "Ocultar Mensagem") e a visibilidade de um parágrafo contendo uma mensagem de boas-vindas com a diretiva `@if`.

4. **Placar Interativo (`/placar`)**
   - Desafio integrador com 3 botões ("Somar 1 Ponto", "Subtrair 1 Ponto", "Zerar Placar"). Possui regra de negócio garantindo que a pontuação nunca fique negativa.

---

## 🚀 Como Executar o Projeto

1. Certifique-se de ter o **.NET SDK** instalado (versão 8+ ou 10).
2. Clone o repositório ou navegue até a pasta do projeto:
   ```bash
   cd SiteUmBlazor
   ```
3. Execute o comando:
   ```bash
   dotnet watch
   ```
   ou
   ```bash
   dotnet run
   ```
4. Acesse o projeto no navegador (por padrão em `http://localhost:5000` ou a porta indicada no terminal).

---

## 📄 Licença (MIT License)

MIT License

Copyright (c) 2026 Eduardo Alves e Santos

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
