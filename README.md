# Teste Técnico Backend

O ambiente do repositório disponibilizado será a base para execução do teste, e já está configurado com:

- Projeto base NestJS + TypeORM + Swagger
- Docker + Docker Compose
- Container com PostgreSQL para a aplicação
- Container com PostgreSQL para o Keycloak
- Container com Keycloak já configurado com usuários e clients

## 🎯 Objetivo

Desenvolver os endpoints RESTful para um CRUD da entidade `products`, com autenticação JWT via Keycloak, persistência com TypeORM e documentação no Swagger.

### 🗃️ Entidade `products`

| Campo        | Tipo       |
|--------------|------------|
| `id`         | UUID       |
| `created_at` | timestamp  |
| `name`       | string     |
| `price`      | decimal    |


### O Keycloak já está configurado com:

- **Realm**: `sysprem`

- **Clients**:
  - `frontend`
  - `backend`
  - `admin-service` (para administração de usuários)

- **User**:
  - name: `teste`
  - pass: `teste`

- **Credenciais do CLI**:
  - user: `admin`
  - pass: `admin`


## Entregas desejáveis:

- CRUD completo da entidade `products`
- Proteção dos endpoints com autenticação via JWT (Keycloak)
- Integração com PostgreSQL utilizando TypeORM
- Documentação completa dos endpoints no Swagger

## Como entregar:

- Faça o commit do seu código na branch main do repositório privado temporário que foi criado para o seu teste.
- Envie uma mensagem informando que o teste foi finalizado.
- Prazo estimado de conclusão: 2 a 4 horas

Boa sorte! 🚀
