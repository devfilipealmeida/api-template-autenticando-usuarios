# Template API de Autenticação de Usuário retornando JWT e validando no Login.

![Node.js](https://img.shields.io/badge/Node.js-v14.17.0-green)
![Express](https://img.shields.io/badge/Express-v4.17.1-blue)
![TypeORM](https://img.shields.io/badge/TypeORM-v0.2.39-orange)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-v13.3-blue)

Esta API contem um endpoint que gera um token JWT e valida antes de conceder acesso as rotas que são encapsuladas pelo Middleware de autenticação.

## Requisitos

- Node.js v14.17.0 ou superior
- PostgreSQL
- Interface de Administração de Banco de Dados (exemplo: Beekeeper)
- Postman (ou outra ferramenta similar) para testar os endpoints

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/filipedower/api-template-autenticando-usuarios.git
```

2. Instale as dependências:

```bash
npm install
```

## Execução

1. Inicie o servidor:

```bash
npm run dev (ambiente de dev)
```
## Contribuição

Contribuições são bem-vindas! Para sugestões, abra uma issue primeiro para discutir o que você gostaria de mudar.

## Licença

Este projeto está licenciado sob a [MIT License](https://choosealicense.com/licenses/mit/).

