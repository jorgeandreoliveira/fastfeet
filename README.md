# FASTFEET
Aplicação para transportadoras

> Instruções para executar a aplicação:

- git clone https://github.com/jorgeandreoliveira/fastfeet

- execute yarn em cada projeto (backend, frontend e mobile)
- execute docker run --name postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres
## backend
- execute yarn sequelize db:migrate
- execute yarn sequelize db:seed:all
- execute yarn dev
## frontend
- execute yarn start
## mobile
- no mobile (Android) execute yarn android
