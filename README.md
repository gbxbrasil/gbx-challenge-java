# Desafio Backend Java

## Introdução
Este cenário foi elaborado seguindo o dia-a-dia de um Desenvolvedor Backend Java na GBX Brasil.

Leia cada requisito atentamente, escolha sua abordagem e mãos à obra.

## Microservico de Transações

### Ideia inicial
Desenhe e codifique um microserviço que será responsável pelas execuções e persistência das transações financeiras requisitadas.

- Siga o approach simplificado de Controller, Service, Repository para facilidade de leitura e organização.
- Utilize tabelas no PostgreSQL para persistência dos dados.
- Cada usuário terá um conta corrente, que será um registro na tabela usuarios (id, nome, número da conta e saldo).
- Persista cada transação como um registro na tabela transações, com conta de origem, conta de destino e valor.
- Execute um número X de transações entre diferentes usuários - onde X > 10.

### Tecnologias
- Java 11+
- Spring Boot
- PostgresSQL
