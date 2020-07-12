![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67](https://user-images.githubusercontent.com/50913322/87230209-c2d41600-c384-11ea-9339-71a8deacfccc.png)


<h1 align="center">:rocket: Desafio 02 do Nível 01 do Bootcamp GoStack 11.0 - Conceitos do Node.js :rocket:</h1>

A proposta deste desafio era testar os conhecimentos do módulo Conceitos do Node.js. Neste desafio proposto foi uma aplicação para testarmos os conceitos que aprendemos neste nível, de criação, listagem, atualização e exclusão de repositórios e seus dados. Além disso, permitir que os usuários possam receber likes em seus repositórios.

### Funcionalidades Implementadas :bookmark_tabs:
- A rota e a função de criar, listar, alterar e deletar um portifólio de repositório. :heavy_check_mark:
- A rota e a função de listar todos os portifólios de repositórios. :heavy_check_mark:
- A rota e a função de curtir um portifólio de repositório. :heavy_check_mark:


### Como Rodar a Aplicação :desktop_computer:


- No terminal, clone o projeto:

```
https://github.com/letbueno/gostack-desafio-nodejs/
```

- Instale as dependências:
```
yarn 
```

- Para executar a aplicação:
```
yarn start
```

### Como testar as requisições 	:technologist:
Para testar as requisições você pode fazer uso de uma API Client, a que eu usei para realizar o projeto foi o [Insomnia](https://insomnia.rest).

- Para cadastrar um portifólio de um repositório: **`POST /repositories`**
- Para listar todos os portifólios de repositórios: **`GET /repositories`**
- Para listar um portifólio de um repositório específico: **`GET /repositories/:id`**
- Para alterar um portifólio de um repositório específico: **`PUT /repositories/:id`**
- Para deletar um portifólio de um repositório específico: **`DELETE /repositories/:id`**

![desafio02](https://user-images.githubusercontent.com/50913322/87248935-76471400-c432-11ea-9407-fb9c7a5b67c9.jpg)


### Como Rodar os Testes? :desktop_computer:
Os testes foram desenvolvidos pela Rocketseat, para testar se as funcionalidades seguem os parâmetros indicados:
- Permitir cadastrar um portifólio de repositório. :heavy_check_mark:
- Permitir listar todos os portifólios de repositório. :heavy_check_mark:
- Permitir alterar um portifólio de repositório específico. :heavy_check_mark:
- Impedir que seja feito a alteração em um portifólio de repositório que não exista. :heavy_check_mark:
- Impedir que seja a rota de alteração de um portifólio específico altere o número de curtidas. :heavy_check_mark:
- Permitir deletar um portifólio de repositório específico. :heavy_check_mark:
- Impedir que seja deletado um portifólio de repositório que não exista. :heavy_check_mark:
- Permitir curtir um portifólio de repositório.  :heavy_check_mark:
- Impedir que um portifólio de repositório que não exista seja curtido. :heavy_check_mark:

Para rodar os testes:
```
yarn test
```
### Dependências e Tecnologias :books: 
- [Node.js](https://nodejs.org/en/docs/)
- [Javascript](https://devdocs.io/javascript/)
- [Typescript](https://www.typescriptlang.org/docs/home.html)
- [Express](https://expressjs.com/pt-br/4x/api.html)
- [Cors](https://www.npmjs.com/package/cors)

### Participante: 
|Name|E-mail|Course|
| -------- | -------- | -------- |
|Leticia Bueno Martins|leticia.bueno.martins@gmail.com|Bootcamp GoStack 11.0|
