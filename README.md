<h2 align="center">Desafio 03 🚀</h2>
<h5 align="center">Ignite - <a href="https://rocketseat.com.br/" >Rocketseat</a> - Trilha Node js</h5>

## 💻 Descrição

Nesse desafio, temos uma aplicação Node.js que está em processo de desenvolvimento mas que já possui os testes necessários para fazer toda a validação dos requisitos.

## 🛠️ Funcionalidades

Essa aplicação realiza o CRUD (**C**reate, **R**ead, **U**pdate, **D**elete) 
de repositórios de projetos. Além disso, é possível dar likes em repositórios cadastrados, 
aumentando a quantidade de likes em 1 a cada vez que a rota é chamada.

## 🔗 Rotas

- POST `/repositories` → criar um repositório.
- POST `/repositories/:id/like` → recebe o like e retorna o repositório com qtd de likes atualizada
- GET `/repositories` → retorna uma lista contendo todos os repositórios cadastrados
- PUT `/repositories/:id` → atualiza  um repositório.
- DELETE `/repositories/:id` → deleta um repositório

### 📝 Clonagem e uso

Para clonar o repositório rode `https://github.com/cecgil/ignite-corrigindo-o-codigo.git` no seu terminal.
Entre na pasta do projeto e rode `yarn` no seu terminal para instalar as dependências.

##### Uso

Com as dependências instaladas rode `yarn dev` para subir o servidor. Para rodar os testes rode `yarn test`.
