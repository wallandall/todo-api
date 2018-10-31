# Todo API

This application is a NodeJS API that uses the Express framework to create, update and delete Todo's

# Installing
## Dependencies
```
  body-parser
  express
  mongodb
  mongoose

```

## Dev Dependencies
```
  expect
  mocha
  nodemon
  supertest

```
To install all dependencies type the below command

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
This test returns 404 error if the todo with an invalid ID is not found

### should return 404 for non-object ids
This test returns error 404 if the specified ID does not convert to a valid ObjectID


## To run the above test type the below command

```
npm run test-watch

```
