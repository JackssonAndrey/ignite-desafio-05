<h2 align="center">Desafio 04 🚀</h2>
<h5 align="center">Ignite - <a href="https://rocketseat.com.br/" >Rocketseat</a> - Trilha Node js</h5>

## 💻 Descrição

Essa aplicação realiza o CRUD (**C**reate, **R**ead, **U**pdate) de usuários. Além disso, é possível tornar um usuário administrador, 
listar usuários apenas se o usuário que estiver solicitando seja administrador. Tudo isso usando conceitos de SOLID.

## 🛠️ Funcionalidades

- Criar um novo usuário com `name`, `email`
- Listar todos os _usuários_;
- Ver perfil do usuário;
- Tornar um usuário administrador;

## 🔗 Rotas

- GET `/get` → lista com todos os usuários.
- POST `/users` → criar um usuário.
- PATCH `/users/:user_id/admin` → tornar um usuário administrador.
- GET `/users/:user_id` → exibe informações do usuário.

### 📝 Clonagem e uso

Para clonar o repositório rode `https://github.com/JackssonAndrey/ignite-desafio-04.git` no seu terminal.
Entre na pasta do projeto e rode `yarn` no seu terminal para instalar as dependências.

##### Uso

Com as dependências instaladas rode `yarn dev` para subir o servidor. Para rodar os testes rode `yarn test`.