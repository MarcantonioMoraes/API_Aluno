# API_Aluno
 API REST completa que realiza operações CRUD (Create, Read, Update, Delete) sobre o cadastro de alunos de uma instituição de ensino, usando Node.js, Express e um ORM para o acesso ao banco de dados PostgreSQL.

# API Aluno

API simples em TypeScript + Express + TypeORM para gerenciar alunos.

## Sobre
Projeto de exemplo que expõe endpoints REST em `/alunos` (criar, listar, atualizar, excluir). O servidor é inicializado em [src/server.ts](src/server.ts) e a conexão com o banco está em [`AppDataSource`](src/database.ts).

## Pré-requisitos
- Node.js
- PostgreSQL

## Variáveis de ambiente
O arquivo de exemplo está em [.env](.env). Atenção: o arquivo atual usa chaves `DB_*`, mas o código em [src/database.ts](src/database.ts) lê `POSTGRES_*`. Atualize uma das partes para ficar consistente. Exemplo de `.env` compatível com o código atual:
