# Projeto Eventos

Este repositório contém os arquivos do front-end e back-end para o projeto Eventos. O objetivo deste projeto é fornecer uma plataforma interativa para gerenciar e visualizar eventos utilizando Vue.js, Node.js, Mongoose e MongoDB.

## Índice

- [Introdução](#introdução)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Configuração](#configuração)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Créditos](#créditos)
- [Licença](#licença)

## Introdução

O projeto Eventos é uma aplicação full stack que permite gerenciar e visualizar eventos. A aplicação utiliza Vue.js no front-end, Node.js no back-end, e Mongoose para interagir com o banco de dados MongoDB. O objetivo é fornecer uma plataforma interativa e robusta para os usuários.

## Funcionalidades

- Design responsivo
- Criação e visualização de eventos
- Autenticação e autorização de usuários
- Integração com banco de dados MongoDB
- Interface de usuário interativa

## Tecnologias Utilizadas

- **Front-End**: Vue.js, Vue Router, Vuex, Vuex Persist, Core-js
- **Back-End**: Node.js, Express, Mongoose, bcrypt, body-parser, cors, jsonwebtoken, multer, nodemon
- **Banco de Dados**: MongoDB

## Configuração

Para rodar este projeto localmente, siga os seguintes passos:

### Front-End

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/Eventos.git
    ```
2. Navegue até o diretório do front-end:
    ```bash
    cd Eventos/frontend
    ```
3. Instale as dependências:
    ```bash
    npm install
    ```
4. Inicie o servidor de desenvolvimento:
    ```bash
    npm run serve
    ```

### Back-End

1. Navegue até o diretório do back-end:
    ```bash
    cd Eventos/backend
    ```
2. Instale as dependências:
    ```bash
    npm install
    ```
3. Inicie o servidor:
    ```bash
    npm start
    ```

## Uso

Uma vez que o projeto esteja configurado, você pode fazer alterações nos arquivos HTML, CSS e JavaScript para personalizar a aplicação de acordo com suas necessidades. Os principais arquivos para edição são:

- **Front-End**:
  - `src/main.js`: O arquivo principal do Vue.js.
  - `src/router/index.js`: O arquivo de configuração das rotas.
  - `src/store/index.js`: O arquivo de configuração do Vuex.
- **Back-End**:
  - `server.js`: O arquivo principal do servidor Node.js.
  - `models/`: O diretório contendo os modelos do Mongoose.
  - `routes/`: O diretório contendo as rotas da aplicação.

## Contribuição

Contribuições são bem-vindas! Se você gostaria de contribuir para este projeto, siga estes passos:

1. Faça um fork do repositório.
2. Crie uma nova branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Faça suas alterações e commite-as:
    ```bash
    git commit -m 'Adicione uma nova funcionalidade'
    ```
4. Faça o push para a branch:
    ```bash
    git push origin feature-branch
    ```
5. Crie um pull request.

## Créditos

Este projeto foi desenvolvido por Lincol N. Almeida.

## Licença

Este projeto é licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Email: [lincolalmeida.sp@gmail.com](mailto:lincolalmeida.sp@gmail.com)
