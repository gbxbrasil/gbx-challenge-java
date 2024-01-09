# Desafio Backend Java

## Introdução
Este cenário foi elaborado seguindo o dia-a-dia de um Desenvolvedor Backend Java na GBX Brasil.

Leia cada requisito atentamente, escolha sua abordagem e mãos à obra.

- Crie um repositório no seu GitHub.
- Faça seus commits no seu repositório.
- Assim que estiver pronto, responda o email do desafio com o link do repositório (lembre de deixar o repositório como **público**).

## Microservico de Transações

### Ideia inicial
Desenhe e codifique um microserviço que será responsável pelas execuções e persistência das transações financeiras requisitadas.

- Siga o approach simplificado de Controller, Service, Repository para facilidade de leitura e organização.
- Utilize tabelas relacionais com o banco de dados de sua preferência para persistência.
- Cada usuário terá um conta corrente, que será um registro na tabela usuarios (id, nome, número da conta e saldo).
- Persista cada transação como um registro na tabela transações, com conta de origem, conta de destino, valor e data da transação.
- Execute um número X de transações entre diferentes usuários - onde X > 10.

Sinta-se livre para aprofundar a implementação do seu serviço, conforme o seu conhecimento, com tratamento de exceções, testes, entre outros itens que julgar conveniente.

### Tecnologias
- Java 11+
- Spring Boot
- SQL
