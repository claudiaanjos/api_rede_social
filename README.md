# API Rede Social

### 📚  Descrição


Projeto desenvolvido para consolidar os conhecimentos de Back-end.

Para esse projeto foi construída uma API de rede social com conexão ao banco de dados, autenticação de usuário (token) e criptografia de senha. A API é composta por:

- Cadastro de usuário;
- Login;
- Cadastro e atualização de postagem;
- Filtro de autenticação;
- Listagem e exclusão de postagens.

A estrutura do projeto:

- *schema.sql*: script de criação das duas tabelas 'usuarios' e 'postagens' da API. O banco de dados rede_social foi criado no Beekeeper;
- *Pasta src*: pasta com o código fonte da API;
- *index.js*: servidor com a porta 3000 liberada;
- *rotas.js*: todas as rotas da API que reedireciona as requisições para um determinado controlador;
- *conexao.js*: realiza a configuração da conexão da API com o banco de dados;
- *Pasta controladores*: pasta com os controladores da API;
- *login.js*: controlador para o usuário logar na rede social;
- *postagens.js*: controlador que realiza a gestão das postagem dos usuários;
- *usuario.js*: controlador para o cadastro do usuário;
- *Pasta filtros*: pasta com o filtro de autenticação;
- *verificaLogin.js*: middleware.


### 🖥️  Recursos utilizados

- [Visual Studio Code](https://code.visualstudio.com/download)
- [NodeJS](https://nodejs.org/en/)
- [Npm](https://www.npmjs.com/)
- [Express](https://expressjs.com/pt-br/)
- [Nodemon](https://nodemon.io/)
- [Insomnia](https://insomnia.rest/download)
- [PostgreSQL](https://www.postgresql.org/)
- [Beekeeper](https://www.beekeeperstudio.io/)
- [JWT (JSON Web Token)](https://jwt.io/)
- [Pg (Node-postgres)](https://www.npmjs.com/package/pg)
- [Bcrypt](https://www.npmjs.com/package/bcrypt)

&nbsp;


<a href="https://www.linkedin.com/in/claudia-nogueira-dos-anjos-b71726215/" target="_blank">
        <img src="https://img.shields.io/badge/claudiaanjos-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&link=mailto:https://www.linkedin.com/in/claudia-nogueira-dos-anjos-093407180/">
</a>