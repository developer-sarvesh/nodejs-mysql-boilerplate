# NodeJS MySQL Boilerplate

This app defines a very neat and modular structure to start you next prject.

Using: MySQL, NodeJS, Express, Bookshelf, Knex

Using ES6, with Babel (http://babeljs.io/)


## Pre-requisites:
1. NodeJS (https://nodejs.org/en/)
2. Globally installed nodemon (https://nodemon.io/)


## Steps to run:
```
git clone git@gitlab.com:raghavgarg1257/nodejs-mysql-boilerplate.git
cd nodejs-mysql-boilerplate
touch .env
nano .env and add your credentials as in env.example (mandatory for db connection)
npm install
```
Now to migrate Database
```
npm install knex -g

# To create the tables
npm run migrate-up

# To drop the tables
npm run migrate-down
```
Now to start the server
```
npm start
```
The app will be started on the mentioned port which will be printed in the console upon starting the server like: `http://localhost:8080`.
