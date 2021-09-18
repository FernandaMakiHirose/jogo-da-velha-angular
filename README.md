# Criando um Jogo da Velha com o Angular
![jogo-da-velha](https://user-images.githubusercontent.com/72028645/133897729-19c824ac-076b-4e61-9c62-605a886f910f.png)
![2](https://user-images.githubusercontent.com/72028645/133897733-fb030235-48fb-4afc-ad6a-862b0e747359.png)

## Requisitos
- Angular CLI
- NodeJS
- NPM

## Como criei o projeto?
Criar o projeto:
>ng new jogo-da-velha

Entrar no projeto:
>cd jogo-da-velha

## Após clonar o projeto, digite no terminal
NPM:
>npm install

Executar um teste:
>ng test

Executar o projeto:
>ng serve

Abra o projeto no navegador:
>http://localhost:4200/

## Como criou um módulo?
>ng g module jogo-da-velha

## Como criou um componente?
>ng g component jogo-da-velha

## Como criou um serviço?
>ng g service jogo-da-velha/shared/jogo-da-velha

## Entendendo o código
`app.module.ts`: É necessário fazer a importação de todos os módulos <br>
`jogo-da-velha.module.ts`: Exportação dos componentes com o "exports" e tem o "providers" que tem os serviços injetados em outros componentes. <br>
`services`: Os serviços apresentam o @Injectable(), onde é possível fazer a injeção de dependência <br>
`index.ts`: O código faz com que não seja preciso passar o nome da classe na importação dos módulos <br>
