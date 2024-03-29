## :ledger: Descrição do Projeto

Essa é uma aplicação que usa a API do [Giphy](https://giphy.com/) para procurar por gifs de acordo com o termo digitado pelo usuário.

<p align="center">
<img alt="gif" src="https://media3.giphy.com/media/nE0RX5y5KAtf3tZSOa/giphy.gif?cid=790b76112fa6720521f27f25e9945de4af3d80d229a6046f&rid=giphy.gif&ct=g" />
</p>

## :man_technologist: Tecnologias

Para este projeto foram utilizadas as seguintes tecnologias:

### BACK-END

- [Node](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Dotenv](https://www.npmjs.com/package/dotenv)
- [Axios](https://axios-http.com/ptbr/docs/intro)

### FRONT-END

- [React](https://pt-br.reactjs.org/)
- [SASS](https://sass-lang.com/)
- [Cypress](https://www.cypress.io/)
- [Axios](https://axios-http.com/ptbr/docs/intro)

## :dvd: Como replicar este projeto

Para replicar esse projeto dno seu computador siga os passos abaixo:

### BACK-END

- Você deve fazer o download/clone [deste](https://github.com/rodhenr/GIF-Search-BackEnd) repositório da parte backend da aplicação e o abrir na sua IDE

```
1. Execute o comando npm i para instalar as dependências do projeto
2. Para conseguir uma API KEY do Giphy faça o cadastro em https://developers.giphy.com/ e gere uma nova chave no dashboard
3. Crie um arquivo .env na raiz do projeto e dentro adicione a linha "SECRET_KEY=suachaveaqui", onde "suachaveaqui" é a chave gerada na sua conta do Giphy. Uma outra alternativa é abrir o arquivo "index.js" e na const key adicionar a sua API KEY.
4. Rode o servidor com o comando "npm run dev"
```

### FRONT-END

- Você deve fazer o download/clone deste repositório e o abrir na sua IDE.

```
1. Execute o comando npm i para instalar as dependências do projeto
2. Execute o comando npm start para rodar localmente na porta 3000
```

Com essas configurações você conseguirá rodar localmente este projeto na sua máquina!

## :grin: Dúvidas ou sugestões?

Caso tenha alguma dúvida ou alguma sugestão fico no aguardo da sua mensagem!

## :computer: Live Demo

Para visualização de uma versão demo do site clique [aqui](https://rodhenr.github.io/GIF-Search-FrontEnd/).
