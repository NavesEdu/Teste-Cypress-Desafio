# Cypress Desafio

- [Sobre](#-sobre)
- [Como executar](#-como-executar)


## 💻 Sobre

Este é um projeto usando Cypress para criação de uma suite de testes para testar a interface do site https://front.serverest.dev/login, nesse projeto são testadas as funcionaldiades de realizar login na aplicação com / sem sucesso, utilizando o browser google chrome:
<br/>

## 🚀 Como executar

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

* [Git](https://git-scm.com/)
* [Visual Studio Code](https://code.visualstudio.com/) como editor de texto, ele será útil para obter as dependências e executar o app.
* [npm](https://www.npmjs.com/package/npm) ou [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable)

### Clonando repositório

Para clonar o repositório em algum lugar na sua máquina, basta utilizar o comando abaixo:
```bash
$ git clone https://github.com/NavesEdu/Teste-Cypress-Desafio
```

### Instalando dependências da aplicação
Recomendamos utilizar o VisualStudio Code, ao abrir o código dentro dele, baixe as dependências pelo terminal:
```
npm install ou yarn install - Instala todas as dependências necessárias.
```

### Iniciando a aplicação
Para ver a aplicação funcionando, abra o terminal do VsCode e digite o comando
```
npx cypress open - Executa a suite de testes com o cypress.
```
* Clique na opção E2E Testing 
!https://user-images.githubusercontent.com/89463362/163295743-1c5b727f-d43f-44b8-a70b-edb84ab44c9a.png
* Selecione o Chrome e clique em Star E2E Testing in Chrome
!https://user-images.githubusercontent.com/92769459/182944559-0da7fe11-e931-4606-9d58-378ca6ef6092.png
* Clique em spec.cy.js para iniciar a suite de testes
!https://user-images.githubusercontent.com/92769459/182944586-9e9987c5-81dc-4cf1-8553-b47c47929e48.png

