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

##Dev Dependencies
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

## To run the above test type the below command

```
npm run test-watch

```
