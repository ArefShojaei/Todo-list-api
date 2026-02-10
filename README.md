<h1 align="center">Todo-list API ✌️</h1>

<p align="center">NodeJS , ExpressJS and MongoDB</p>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" alt="express logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="mongodb logo"  />
</div><br><br>

<a href="https://todo-list-api-666z.onrender.com/api/todos/" alt="Postman"><img src="https://github.com/ArefShojaei/todo-list-api/assets/134844185/cf8f495d-bd9d-4121-a132-166472624397" /></a>


<h2 align="left">How to use it?</h2>

> First step:

Install all package dependencies from NPM
```bash
npm install
```

> Second step:

After installing packages, then create ".env" file in root of the project and add these variables
```bash
APP_PORT = 3000
MONGODB_URL = mongodb://127.0.0.1:27017/database_name
```
###
###
###

<h2 align="left">API End-points + HTTP methods</h2>

###
> Create new Todo
```txt
[POST] /api/todos
```

> Get all Todos
```txt
[GET] /api/todos
```

> Get Todo by ID
```txt
[GET] /api/todos/:id
```

> Update Todo by ID
```txt
[PATCH] /api/todos/:id
```

> Delete Todo by ID
```txt
[DELETE] /api/todos/:id
```

> Delete all Todos
```txt
[DELETE] /api/todos
```
