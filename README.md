# Shopping Cart API

REST API desenvolvida com Java e Spring Boot para gerenciamento de uma sacola de compras.

Este projeto simula um sistema de e-commerce, permitindo adicionar, listar, atualizar e remover itens da sacola.

## Tecnologias
- Java
- Spring Boot
- Spring Data JPA
- H2
- Maven

## Funcionalidades
- Criar item na sacola
- Listar itens
- Atualizar quantidade
- Remover item
- Escolher a forma de pagamento

## Arquitetura
Projeto estruturado seguindo o padrão:
- Controller
- Service
- Repository
- Entity

## Como rodar o projeto
git clone https://github.com/GhostRiley115/Projeto-SacolaCompras-SpringApi
1.	Abrir no IntelliJ
2.	Rodar a aplicação
3.	Acessar: http://localhost:8080

## Endpoints
GET /items : listar itens
POST /items : criar item
PUT /items/{id} : Atualizar item
DELETE /items/{id} : Remover item

## Objetivo
Praticar desenvolvimento de APIs REST utilizando Spring Boot e boas práticas de organização em camadas.
