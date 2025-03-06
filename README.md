```
npm install sequelize pg pg-hstore

sudo npm install -g sequelize-cli 

sequelize init

sequelize

sequelize db:create

sequelize model:generate --name User --attributes name:string,email:string,role:string

npm install express

sequelize db:migrate

sequelize model:generate --name Post --attributes body:string

sequelize db:migrate:status

sequelize db:migrate:undo  // revert the latest migration

sequelize db:migrate:undo:all // revert all migration
```


```
\c sequelize_db
\dt
\d "Users"   \\"" needed for uppercase U

DROP TABLE "Users"

select * from users;



```