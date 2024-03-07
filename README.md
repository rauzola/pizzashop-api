# 🍕 pizza.shop API

Aplicativo de entrega de comida (também conhecido como iFood/Uber Eats) back-end construído com TypeScript, Drizzle e ElysiaJS.

> 🔥 Este projeto tem como objetivo manter-se agnóstico em tempo de execução, o que significa que deve funcionar no Bun, Node, Cloudflare Workers ou em qualquer tempo de execução compatível com API padrão da web.

## Running

Este projeto depende do Docker para configurar o banco de dados. Com o Docker instalado, clone o projeto, instale as dependências, configure os contêineres do Docker e execute a aplicação.

> Você também deve executar migrações para criar tabelas no banco de dados e executar o seed para popular o banco de dados com dados falsos.

```sh
bun i
docker compose up -d
bun migrate
bun seed
bun dev
```

## Features

> O resumo dos recursos está listado abaixo. Todos os recursos contêm testes E2E.

- deve ser capaz de registrar um novo restaurante
- deve ser capaz de fazer login como gerente de restaurante
- deve ser capaz de se registrar como um novo cliente
- deve ser capaz de criar um pedido para o restaurante
- deve ser capaz de gerenciar o menu do restaurante
- deve ser capaz de gerenciar as avaliações do restaurante
- deve ser capaz de deixar uma avaliação
- deve ser capaz de gerenciar os pedidos do restaurante
- deve ser capaz de atualizar o perfil público do restaurante
- deve ser capaz de abrir/fechar o restaurante
- deve ser capaz de listar métricas do restaurante