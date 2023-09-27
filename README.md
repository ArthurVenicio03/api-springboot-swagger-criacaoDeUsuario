# API RESTful de Gerenciamento de Usuários

Esta é uma API RESTful desenvolvida com Spring Boot que permite a criação, visualização e exclusão de usuários. Ela utiliza o Swagger para documentação e é escrita em Java.

## Requisitos

Certifique-se de que você possui as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:

- Java Development Kit (JDK) 11 ou superior
- Spring Boot
- Maven
- Um cliente API, como o Postman, para testar as operações

Documentação Swagger

Você pode acessar a documentação da API utilizando o Swagger. Abra o navegador e acesse:

bash

http://localhost:8080/swagger-ui.html

Isso exibirá a interface Swagger, onde você pode explorar e testar as operações da API.
Endpoints

A API possui os seguintes endpoints:

    POST /api/usuarios: Crie um novo usuário enviando um JSON com os dados do usuário.
    GET /api/usuarios: Obtenha a lista de todos os usuários cadastrados.
    GET /api/usuarios/{id}: Obtenha os detalhes de um usuário específico pelo seu ID.
    DELETE /api/usuarios/{id}: Exclua um usuário pelo seu ID.

Exemplo de Requisições

Aqui estão alguns exemplos de como usar a API com o cliente API:

    Criar um novo usuário:

    http

POST http://localhost:8080/api/usuarios
Content-Type: application/json

{
  "nome": "João Silva",
  "email": "joao@example.com"
}

Obter a lista de todos os usuários:

http

GET http://localhost:8080/api/usuarios

Obter os detalhes de um usuário específico (substitua {id} pelo ID real do usuário):

http

GET http://localhost:8080/api/usuarios/{id}

Excluir um usuário específico (substitua {id} pelo ID real do usuário):

http

    DELETE http://localhost:8080/api/usuarios/{id}

Lembre-se de que este é um exemplo simples e que você pode personalizar e expandir a API de acordo com suas necessidades.
Contribuindo

Sinta-se à vontade para contribuir com melhorias, relatar problemas ou adicionar recursos à API. Abra uma issue ou envie um pull request com suas alterações.
Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter detalhes.



