# API para Gerenciamento de Produtos

Este projeto é uma API RESTful para o gerenciamento de produtos, implementada usando Spring Boot. A API permite realizar operações básicas de CRUD (Create, Read, Update, Delete) em produtos.

## Tecnologias Utilizadas

- **Java 21**: Linguagem de programação utilizada.
- **Spring Boot 3.3.2**: Framework para simplificar o desenvolvimento de aplicações Java.
- **Spring Data JPA**: Para persistência de dados e interação com o banco de dados.
- **H2 Database**: Banco de dados em memória para desenvolvimento e testes.
- **PostgreSQL**: Banco de dados relacional para ambiente de produção.
- **Springdoc OpenAPI**: Para documentação automática da API (Swagger UI).
- **Maven**: Ferramenta de automação de build e gerenciamento de dependências.

## Funcionalidades

- **Criação de Produtos**: Adiciona novos produtos ao banco de dados.
- **Leitura de Produtos**: Recupera a lista completa de produtos ou busca um produto específico pelo ID.
- **Atualização de Produtos**: Atualiza as informações de um produto existente.
- **Exclusão de Produtos**: Remove um produto do banco de dados pelo ID.

## Endpoints da API

- **GET /produtos**
  - Retorna a lista de todos os produtos.
  
- **GET /produtos/{id}**
  - Retorna um produto específico pelo ID.
  
- **POST /produtos**
  - Cria um novo produto.
  
- **PUT /produtos/{id}**
  - Atualiza um produto existente pelo ID.
  
- **DELETE /produtos/{id}**
  - Remove um produto pelo ID.

