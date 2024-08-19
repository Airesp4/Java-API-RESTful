# Java API RESTful

Este projeto é uma API RESTful desenvolvida com Spring Boot e Java 17. A API permite gerenciar produtos com operações CRUD básicas e fornece documentação interativa usando OpenAPI.

## Tecnologias Utilizadas

- **Java 17**: Versão LTS do Java.
- **Spring Boot 3**: Framework para criação de aplicações Java.
- **Spring Data JPA**: Para acesso e manipulação de dados.
- **H2 Database**: Banco de dados em memória para desenvolvimento e testes.
- **Springdoc OpenAPI**: Para geração da documentação da API.

## Funcionalidades

- **Produto**: Entidade principal com os atributos `id`, `nome`, e `preço`.
- **Endpoints**:
  - `GET /produtos` - Lista todos os produtos.
  - `POST /produtos` - Cria um novo produto.
  - `GET /produtos/{id}` - Obtém um produto específico por ID.
  - `PUT /produtos/{id}` - Atualiza um produto existente.
  - `DELETE /produtos/{id}` - Remove um produto por ID.

## Configuração

### Pré-requisitos

- Java 17
- Maven

### Clonar o Repositório

Clone o repositório para o seu ambiente local:

```sh
git clone https://github.com/seu-usuario/Java-API-RESTful.git
cd Java-API-RESTful
