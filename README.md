API REST para gestão de clínica e laboratório desenvolvida com Spring Boot.

## 🚀 Tecnologias
- Java 21
- Spring Boot 3
- Spring Data JPA
- Spring Security (JWT)
- PostgreSQL
- Flyway
- Docker
- Testcontainers
- OpenAPI (Swagger)

## 📌 Funcionalidades
- Autenticação e autorização por perfil
- Cadastro de pacientes
- Gestão de exames e convênios
- Pedido de exames com fluxo de status
- Emissão de laudos
- Auditoria de ações
- Paginação e filtros

## 🏗️ Arquitetura
- Controller / Service / Repository
- DTOs
- Validações
- Tratamento global de erros

## ▶️ Como executar
```bash
docker compose up -d
mvn spring-boot:run
