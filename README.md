📌 Forum Hub — Documentação

Autor: Andre Barbosa
Versão: 2.5 — Finalizada, dockerizada e entregue.
Stack: Java 17 + Spring Boot 2.5 + PostgreSQL + Docker

🚀 Descrição

O Forum Hub é uma aplicação para gerenciamento de fóruns, permitindo criação, edição, listagem e exclusão de usuários, tópicos e respostas.
Autenticação via JWT e suporte completo para execução via Docker.

🛠 Tecnologias

Java — Linguagem principal

Spring Boot — Framework backend

PostgreSQL — Banco de dados

Docker — Conteinerização

IntelliJ IDEA — IDE de desenvolvimento

🖥 Instalação Local
git clone https://github.com/AndreGBarbosa/Forum-Hub.git
cd ForumHub
sudo docker-compose build
sudo docker-compose up


Ou com Maven:

./mvnw spring-boot:run


Swagger: http://localhost:8080/swagger-ui/index.html#/

🔑 Pré-requisitos

Internet

Docker
(Java 17, IntelliJ e Maven opcionais)

📋 Funcionalidades

CRUD de usuários, tópicos e respostas

Autenticação via JWT

Execução simples via Docker
