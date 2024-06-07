# Cartões-MS

## Descrição

O `cartoes-ms` é um microservice responsável por gerenciar propostas de crédito, emitir cartões e gerenciar clientes.

## Dependências

- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database
- Spring Boot Starter Validation
- Spring Boot Starter Test

## Configuração
no caminho src/main/java/com/ms/cartoes/config/ tem as configurações:
- CorsConfig
- ModelMapperConfig
- SwaggerConfig


### Banco de Dados

Este microservice utiliza o banco de dados H2 para persistência de dados. a configuração do banco é a padrão do spring, runtime, os dados serão mantidos enquanto aplicação estiver rodando.

## Documentação
Swagger: http://localhost:8080/swagger-ui/index.html