# App

Este projeto foi gerado com a versão 12.2.9 do [Angular CLI](https://github.com/angular/angular-cli).

## Install Version Angular

Para instalar a versão do Angular 12.2.9, execute no terminal `npm install -g @angular/cli@12.2.9`, assim você vai instalar a versão que está sendo utilizada nesse projeto.

## Erro 0308010C, só se caso ocorrer!!!

Caso ocorra o erro 0308010C, não se preocupe, isso ocorre devido à conflitos de versão do Node, basta executar os seguintes comandos no terminal, se for LINUX e macOS:` export NODE_OPTIONS=--openssl-legacy-provider `, se for Prompt de comando do Windows:` set NODE_OPTIONS=--openssl-legacy-provider ` ou Windows PowerShell: ` $env:NODE_OPTIONS = "--openssl-legacy-provider" `


## Development server

Execute `ng serve` para iniciar um servidor de desenvolvimento. Acesse `http://localhost:4200/` no navegador. O aplicativo será recarregado automaticamente se você modificar algum dos arquivos de origem.

## Code scaffolding

Execute `ng generate component component-name` para gerar um novo componente. Você também pode usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para compilar o projeto. Os artefatos de compilação serão armazenados no diretório  `dist/`.

## Running unit tests

Execute `ng test` para executar os testes unitários via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Execute `ng e2e` para executar os testes end-to-end usando uma plataforma de sua escolha. Para usar este comando, você precisa primeiro adicionar um pacote que implemente as capacidades de teste end-to-end.

## Further help

Para obter mais ajuda sobre o Angular CLI, use `ng help` ou consulte a [visão geral e referência de comandos do Angular CLI](https://angular.io/cli).
