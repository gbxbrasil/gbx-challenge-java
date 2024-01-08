# Desafio Backend Java

## Introdução
Este cenário foi elaborado seguindo o dia-a-dia de um Desenvolvedor Backend Java na GBX Brasil.

Leia cada requisito atentamente, escolha sua abordagem e mãos à obra.

## Microservico de Transações

### Ideia inicial
Desenhe e codifique um microserviço que será responsável pelas execuções e persistência das transações financeiras requisitadas.

- Deverá conter ao menos 1 tabela no PostgresSQL.
- Siga o approach simplificado de Controller, Service, Repository para facilidade de leitura e organização.
- Os dados dos usuários (nome, chave pix, saldo de conta corrente) pode ser adicionado como Mock ou em uma tabela, como preferir.
- Utilize um serviço simplificado para autenticação do usuário logado. Exemplo: ``` if(token.equals("tokenEsperado") return true ```
- Execute um número X de transações entre diferentes usuários, persistindo na tabela.
