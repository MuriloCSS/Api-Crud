# 📦 API RESTful com Flask - CRUD Completo

Este projeto é uma API RESTful simples com suporte a operações **CRUD (Create, Read, Update, Delete)**. A aplicação foi desenvolvida com foco em aprendizado e prática com as principais ferramentas do ecossistema Flask.

## 🚀 Tecnologias utilizadas

- [Flask](https://flask.palletsprojects.com/) — microframework web Python
- [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/) — ORM para integração com banco de dados
- [SQLite/PostgreSQL](https://www.sqlite.org/index.html) — banco de dados relacional (dependendo do ambiente)
- [Docker](https://www.docker.com/) — containerização da aplicação
- [Postman](https://www.postman.com/) — para testes das rotas

## 📡 Rotas da API

| Método | Endpoint        | Descrição                  |
|--------|------------------|-----------------------------|
| GET    | `/users`         | Lista todos os usuários     |
| GET    | `/users/<id>`    | Lista um usuário por id     |
| POST   | `/users`         | Cria um novo usuário        |
| PUT    | `/users/<id>`    | Atualiza um usuário por ID  |
| DELETE | `/users/<id>`    | Remove um usuário por ID    |

## 🧪 Como testar

Você pode utilizar o **Postman** ou **Insomnia** para fazer requisições HTTP às rotas da API.

## 🐳 Rodando com Docker

**Clone o repositório**

git clone https://github.com/MuriloCSS/Api-Crud.git
cd Api-Crud

**Construa a imagem**

docker compose build

**Suba os containers (aplicação + banco de dados)**

docker compose up -d

**Acesse a API em: http://localhost:4000**


