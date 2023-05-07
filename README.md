# Projeto Commerce

Projeto realizado durante módulo de Back-end do curso de desenvolvimento web da Trybe.

  <summary><strong>O que foi feito</strong></summary></br>

  Neste projeto coloquei em prática métodos e operadores para alterar dados no banco de dados não relacional commerce (MongoDB).
  A aplicação foi desenvolvida com:

- `MongoDb`
- `mongosh`
- `docker`

  <summary><strong>Como rodar o projeto</strong></summary></br>

  **Com Docker:**

  **:warning: Antes de começar, seu docker-compose precisa estar na versão 1.29 ou superior.

- `docker run -d --name=mongo-commerce -v "$PWD:/app" -p 27017:27017 mongo:5.0`
- `docker exec -it mongo-commerce bash`
- `cd app/`
- `mongorestore -d commerce -c produtos assets/produtos/produtos.bson`

**Localmente:**

**Necessita ter um banco de dados(MongoDb) instalado localmente**
