## Samurai BS Automação Web - Cypress
Esse é um repositório que contém a automação de alguns testes Web de um software denominado Samurai Barber Shop, um sistema de Gestão de Barbearia. Os sub-tópicos abaixo descrevem algumas decisões tomadas da estruturação do Projeto.

## Tecnologias Utilizadas

Cypress - https://www.cypress.io/
CLI com Gitbash e Hyper - https://hyper.is https://gitforwindows.org
Nodejs 16 LTS - https://nodejs.org
Elephant SQL - https://www.elephantsql.com/

## Testes Automatizados
Testes para validar os campos de Cadastro de usuário, Login, Solicitação de Recuperação de Senha, Alteração de Senha e Validação de Agendamento no Dashboard do profissional que trabalha na Samurai Barber Shop.

## Notas Gerais

-   Criei cenários de testes independentes entre si;
-   Para cada automação criei Page Objects index.js para armazenar as classes criadas;
-   Para cada automação criei uma camada de elementos elements.js inserir os elementos mapeados através de seletores CSS;
-	Armazenei as massas de testes em arquivos .JSON na pasta fixtures;
-	Criei comandos customizados na camada commands.js dentro da pasta pages;
-   Nesse Projeto fiz uso do Nodejs 16 LTS, o que me permitiu rodar a linguagem de programação JavaScript;