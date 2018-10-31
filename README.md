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
# Running the tests

### should create a new todo

This tests if a new Todo can be created and expects a 200 code to be returned

### should not create todo with invalid body data
This test checks for the creation of invalid entries and expects a return code of 400 if there is no text submitted

### should get all todos
This test passes if the test returns two Todo's from the database.

### should return todo doc
This test returns 200 if a search returns a document with the specified ID.

### should return 404 if todo not found

### should return 404 for non-object ids
This test returns error 404 if the specified ID does not convert to a valid ObjectID

### should remove a todo
This test returns 200 if a Todo is succefuly deleted

### should return 404 if object id is invalid
This test returns error 404 if the specified ID does not convert to a valid ObjectID when deliting a Todo

### should return 404 if todo not found
This test returns error 404 if the ID is not found when deleting a Todo

### should update the todo
This test returns 200 if the text of a Todo is updated, completed set to true and completedAt set to a number

### should clear completedAt when todo is not completed
This test returns 200 if the text of a Todo is updated, the completed is set t false and clears the completedAt field


## To run the above test type the below command from the application directory

```
npm run test-watch

```
## Endpoints
### Todo
- GET todo
- GET todo/id
- POST todo
- DELETE todo/id
- PATCH todo/id

### User
