# Basic API CRUD with Node Express

## Create App
```
$ cd node-easy-notes-app
$ npm init
$ npm install express body-parser mongoose --save

$ node server.js 
http://localhost:3000/

$ mkdir config
$ cd config

$ mkdir -p app/models
$ cd app/models

$ mkdir app/routes
$ cd app/routes
```

## Postman:
- Get All:
http://localhost:3000/notes

- Get By ID:
http://localhost:3000/notes/5d3c676642fa17478094b580

- Post:
http://localhost:3000/notes
```
{
    "title": "My First Note 206",
    "content": "This is my first note in EasyNotes application 206"
}
```

- Edit(PUT):
http://localhost:3000/notes/5d3c676642fa17478094b580
```
{
    "title": "My First Note 206 edit",
    "content": "This is my first note in EasyNotes application 206 edit"
}
```

- Delete:
http://localhost:3000/notes/5d3c676642fa17478094b580


## Main article: 
https://www.callicoder.com/node-js-express-mongodb-restful-crud-api-tutorial/

## Important site:
- https://github.com/nodejs/node
- https://github.com/expressjs/express
- https://expressjs.com/
- https://expressjs.com/en/5x/api.html
- https://github.com/sindresorhus/awesome-nodejs
- https://github.com/sqreen/awesome-nodejs-projects
- https://nodejs.org/en/
- https://github.com/github/gitignore
- https://github.com/github/gitignore/blob/master/VisualStudio.gitignore

