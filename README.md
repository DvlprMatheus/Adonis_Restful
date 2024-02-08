# API Restful

O AdonisJS é um framework web em TypeScript para NodeJS, onde você pode construir aplicações web full-stack ou JSON API server. E neste projeto, o foco principal é desenvolver uma API Restful que irá servir um site chamado Moments, um estilo de rede social, desenvolvido em Angular pelo curso do Hora de Codar.

## Sumário

- [Como Usar](#como-usar)
- [Tecnologias](#tecnologias)
- [Testes](#testes)
- [Licença](#licença)

## Como Usar

Após realizar o **$git clone** ou **download em .zip**, abra em sua IDE e faça as instalações de suas dependências necessárias. Começando pelo `npm install`, que irá baixar a node_modules em seu projeto, essencial para inicia-lo. Após a conclusão, utilize o comando `node ace generate:key` que irá gerar um token para configurar o APP_KEY no arquivo **.env** na pasta principal, renomeie retirando o **.example**. Por fim, use `node ace migration:run` para criar o banco de dados no SQLite, e `node ace serve` para iniciar o serviço da API.

## Tecnologias

![Tecnologias](https://skillicons.dev/icons?i=adonis,typescript)

## Testes

Para realizar testes, você pode utilizar interfaces que simulam requisição HTTP, como Postman ou Insomnia. Depois de iniciar sua aplicação, dê uma olhada na pasta **start** onde tem o arquivo routes.ts, que como diz o nome, indica os endpoints disponibilizados para acessar o CRUD.

## Licença
Nenhuma e é totalmente livre para todos.
