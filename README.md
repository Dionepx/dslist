
# Projeto Java com Spring Boot e Maven

Projeto backend simples usando Java 21, Spring Boot 3.4.1 e JPA para gerenciar listas de jogos.

## Tecnologias usadas

- Java 21  
- Spring Boot 3.4.1  
- Spring Data JPA  
- Maven  
- Banco H2 (runtime)  
- PostgreSQL (runtime)  

## Como rodar

1. Clone o repositório  
   ```bash
   git clone https://github.com/seu-usuario/dslist.git

2. Entre na pasta do projeto: cd dslist

4. Rode a aplicação

  ./mvnw spring-boot:run

## Buscar jogo por id

GET /games/{id}

## Listar todos os jogos

GET /games

## Listar todas as listas de jogos

GET /lists

## Listar jogos de uma lista específica

GET /lists/{listId}/games
