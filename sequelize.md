- > npm init -y
- > npm i sequelize pg pg-hstore
- > npm install --save-dev sequelize-cli
- > npx sequelize-cli init
- > npx sequelize-cli model:generate --name User --attributes email:string
-   "scripts": {
    "make-model": "npx sequelize-cli model:generate --name user --attributes email:string",
    "migrate": "npx sequelize-cli db:migrate",

- > npm run migrate