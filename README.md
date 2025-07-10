# 📡 Perguntas Frequentes com IA - API (NLW 20)

API desenvolvida durante a **NLW 20 da Rocketseat**, com o objetivo de criar salas de perguntas frequentes, onde usuários podem responder questões ou receber respostas automáticas com ajuda de inteligência artificial.

## 🚀 Tecnologias

- [Fastify](https://www.fastify.io/)
- [Drizzle ORM](https://orm.drizzle.team/)
- [Zod](https://zod.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker Compose](https://docs.docker.com/compose/)
- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) (para testes locais via `client.http`)

## 📦 Requisitos

- [Node.js](https://nodejs.org/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- Extensão **REST Client** (opcional, para testes rápidos)

## 🛠️ Como rodar o projeto

1. **Clone o repositório**
```bash
    git clone https://github.com/loanmatteusz/letmeask-api.git
    cd letmeask-api
```

2. **Suba o banco de dados com Docker**
```bash
    docker-compose up -d
```

3. **Instale as dependências**
```bash
    npm install
```

4. **Execute as migrações e popule o banco com dados iniciais**
```bash
    npx drizzle-kit generate
    npx drizzle-kit migrate

    npm run db:seed
```

5. **Inicie a aplicação em modo desenvolvimento**
```bash
    npm run dev
```

6. **Agora teste a API usando o arquivo client.http com a extensão REST Client no VSCode.**

