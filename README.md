# Projeto de Microsserviços: AutorService e Livraria

Este repositório contém dois microsserviços, **AutorService** e **Livraria**, desenvolvidos com **Spring Boot** e configurados para se comunicar utilizando **RabbitMQ**. Eles estão preparados para serem conteinerizados com **Docker** e orquestrados com **Kubernetes**.

## Funcionalidades

### AutorService
- CRUD de autores.
- Comunicação com Livraria via RabbitMQ.

### Livraria
- CRUD de livros, vinculando autores (consome autores via RabbitMQ).
- Histórico de livros, guardando as alterações realizadas.

## Tecnologias Utilizadas
- **Java 17** (via Spring Boot)
- **RabbitMQ** (para comunicação assíncrona entre microsserviços)
- **Docker** (para conteinerização)
- **Kubernetes** (para orquestração)
- **MySQL** (como banco de dados, opcional)

## Estrutura do Projeto

