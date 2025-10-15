API REST de Cadastro de Livros

Este projeto foi desenvolvido como parte do curso “Node.js: criando uma API Rest com Express e MongoDB”.
O objetivo foi construir uma API RESTful para gerenciar um catálogo de livros, aplicando boas práticas de desenvolvimento backend com Node.js, Express e MongoDB.

🚀 Tecnologias Utilizadas

Node.js — ambiente de execução JavaScript no servidor

Express.js — framework para criação de APIs REST

MongoDB — banco de dados NoSQL para armazenar informações dos livros

Mongoose — modelagem de dados e comunicação com o MongoDB

Nodemon — reinicialização automática durante o desenvolvimento

⚙️ Funcionalidades

✅ Listar livros — retorna todos os livros cadastrados

🔍 Buscar livro por ID

➕ Cadastrar novo livro

✏️ Atualizar informações de um livro

❌ Excluir livro do catálogo

⚙️ Estrutura organizada em Models, Controllers e Routes

⚡ Middleware de tratamento de erros e validação básica

📁 Estrutura do Projeto
📦 api-livros

├── 📁 src

│   ├── 📁 config

│   ├── 📁 controllers

│   ├── 📁 models

│   ├── 📁 routes

│   └── server.js
├── .env

├── package.json

└── README.md


📘 Conceitos Aplicados

CRUD completo com MongoDB

Arquitetura MVC (Model, View, Controller)

Modularização e boas práticas no Express

Uso de variáveis de ambiente (.env)

Tratamento de erros e respostas HTTP

💡 Aprendizados

Durante o desenvolvimento deste projeto, aprendi a:

Criar uma API REST do zero com Node.js e Express;

Conectar e manipular dados em um banco MongoDB usando Mongoose;

Estruturar o código de forma limpa e reutilizável;

Testar rotas e métodos HTTP com ferramentas como Insomnia e Postman.

🧠 Possíveis Melhorias Futuras

Implementar autenticação JWT

Adicionar validações mais robustas com Joi ou Express Validator

Criar uma interface front-end para consumir a API

Adicionar paginação e busca avançada

👨‍💻 Autor

Gustavo Parizi
🎓 Estudante de Ciência da Computação | 🔐 Foco em Cibersegurança e Desenvolvimento Backend Node.js
🔗 LinkedIn: https://www.linkedin.com/in/gustavo-parizi
