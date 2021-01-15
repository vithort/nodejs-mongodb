# nodejs-mongodb

Tutorial CRUD em Node.js com driver nativo do MongoDB

- Link: [Tutorial CRUD em Node.js com driver nativo do MongoDB](https://www.luiztools.com.br/post/tutorial-crud-em-node-js-com-driver-nativo-do-mongodb/)

- Link: [Tutorial CRUD em Node.js com driver nativo do MongoDB – Parte 2](https://www.luiztools.com.br/post/tutorial-crud-em-node-js-com-driver-nativo-do-mongodb-2/)

- Link: [Tutorial CRUD em Node.js com driver nativo do MongoDB – Parte 3](https://www.luiztools.com.br/post/tutorial-crud-em-node-js-com-driver-nativo-do-mongodb-3/)

## Comandos:

- Iniciar Repositório

```npm
npm init
```

- Instalar o Express Generator

```npm
npm install -g express-generator
```

- Iniciar uma Aplicação Express com Motor EJS

```npm
express -e
```

- Instalar Dependências

```npm
npm install
```

- Iniciar Aplicação

```npm
npm start
```

### Acessar em

```
http://localhost:3000
```

- Executar MongoDB no CMD

```cmd
$ mongod --dbpath D:\Workspace\nodejs-mongodb\data
```

- Executar em outro Terminal

```cmd
mongo
```

- Usar Banco de Dados

```mongo
use workshoptdc
```

- Inserir Dados pelo CMD

```mongo
db.customers.insert({ "nome" : "Vithor", "idade" : 38 })
```

- Buscar Dados pelo CMD

```mongo
db.customers.find().pretty()
```

- Adicionar mais Registros

```mongo
custArray = [{ "nome" : "Fernando", "idade" : 29 }, { "nome" : "Teste", "idade" : 20 }]
db.customers.insert(custArray);
```

- Instalar Mongodb

```npm
npm install mongodb --save
```
