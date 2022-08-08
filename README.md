# Cypress Desafio

- [Sobre](#-sobre)
- [Como executar](#-como-executar)


## 💻 Sobre

Este é um projeto usando Cypress para criação de uma suite de testes para testar a interface do site https://front.serverest.dev/login, nesse projeto são testadas as funcionalidades de realizar login na aplicação com / sem sucesso, utilizando o browser google chrome:
</p>
<p aligng="center">
  <img width"450" height="300" src="to_ReadME/readme4.png">
</p>
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
</p>
<p aligng="center">
  <img width"450" height="300" src="to_ReadME/readme1.png">
</p>

* Selecione o Chrome e clique em Star E2E Testing in Chrome
</p>
<p aligng="center">
  <img width"450" height="300" src="to_ReadME/readme2.png">
</p>

* Clique em spec.cy.js para iniciar a suite de testes
</p>
<p aligng="center">
  <img width"450" height="300" src="to_ReadME/readme3.png">
</p>

