# Flyway Demo 

Projeto de exemplo com Spring Boot, Flyway e H2 para gerenciar migrações de banco e expor uma API REST de produtos.


## Dependências
- Spring Web
- Spring Data JPA
- H2 Database (memória)
- Flyway Core

## Como executar
Clonar o repositório:
```bash
git clone https://github.com/ucarols/cp5Java.git
```
Entrar na pasta do projeto:
```bash
cd cp5Java
```
cmd:
```powershell
mvn spring-boot:run
```

Base URL: `http://localhost:8080`


## Endpoints
- Listar todos: `GET /produtos`
- Buscar por ID: `GET /produtos/{id}` (404 se não existir)
- Criar: `POST /produtos`


