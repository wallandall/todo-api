# Todo API

This application is a NodeJS API that uses the Express framework to create, update and delete Todo items

# Demo

Here is a working live demo: https://webe-todo-api.herokuapp.com


# Installing
## Dependencies
```
  body-parser
  express
  mongodb
  mongoose
  lodash
  validator
  jsonwebtoken
  bcryptjs

```

## Dev Dependencies
```
  expect
  mocha
  nodemon
  supertest

```
To install all dependencies type the below command from the application directory

```
npm install

```
# Running the program

## Environment Variables
- PORT
  - Defines the Port the application runs on
- MONGODB_URI
  - Defines the URL for MongoDB
- NODE_ENV
  - The Node Environment eg: production, test or development
- JWT_SECRET
  - The Secret Key used to generate tokens

## To to run the program type the below command from the application directory

```
npm start

```

## To run the all tests type the below command from the application directory

```
npm run test-watch

```
## Endpoints
### Todo
- GET todos
- GET todos/id
- POST todos
- DELETE todos/id
- PATCH todos/id

### User
- POST users
- GET users
- GET users/me
- POST users/login
- DELETE /users/me/token
