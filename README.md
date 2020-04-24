# Assignment1

# Express Example

This repository demonstrates the usage of Sequelize within an [Express](https://expressjs.com) application.
The implemented logic is a simple task tracking tool.

## Configuration

Configuration can be found in `config/config.js`

### Environment vaiables used to configure the application

- DB_USERNAME - username for the database server
- DB_PASSWORD - password for the database server
- DB_NAME - name of the database
- DB_HOSTNAME - hostname of the database server

## Starting App

*Without Migrations*

```
npm install
npm start
``
**With Migrations**

```
npm install
node_modules/.bin/sequelize db:migrate
npm start
```

This will start the application and create an sqlite database in your app dir.
Just open [http://localhost:3000](http://localhost:3000).

## Building the docker image

TODO

## Running Tests

### Unit tests

There are [Mocha](https://mochajs.org) based unit test in the application. 

### Linting

TODO: add ESLint command

### Code coverage

TODO: Add istanbul(nyc) commands

### Integration tests

Integration tests are implemented using Mocha as well. 

TODO: set up integration test environment and run integration tests


### End to end test

E2E tests are implemented using QaWolf and requires a database backend to execute properly.

Set the environment variable `QAW_HEADLESS` to true to run the e2e in headless mode

https://www.qawolf.com/

TODO: Set up e2e test environment and run the e2e tests

![](Images/git%20ss.png)

This is a screen shot of my github account which shows the repository named Assignemnt 1 in which I have created all my branches and the project. Github is one of the element which we have used for this project as recommended by our experienced staff. This is a wide used software and is very easy to use.

SS2 (Circle CI)

This screenshot shows the execution of circle ci with the URL visble on the top which shows that it is linked to my github account with the repository named Assignment 1.

SS3 (Unit Testing)

This Screenshot shows the sccessfull execution of unit tests in circle ci. We have used mocha to complete unit tests. The reason behind using mocha is We like frameworks that are easy to use, open-source, flexible and have a great support community.

SS3 (Integration Testing)

This Screenshot shows the sccessfull execution of integration tests in circle ci. in this also we have used mocha to complete integration tests. The reason behind using mocha is We like frameworks that are easy to use, open-source, flexible and have a great support community.

SS4 (Lint)

This Screenshot shows the sccessfull execution of linting in circle ci. Here are some benefits of using lint eslint in our project,
You will find bugs and errors before they happen.
You will spend less time testing new features.
Your code will be more consistent.

SS5 (Code Coverage)

This ScreenShot shows the successfull execution of code coverage. This is basically an important step to execute. It mostly covers around 80% of the code which have been tested.

SS6 (Failing Scenario)

This screenshot shows a failing scenario. I did a small change in a index.test.js which is in unit directory under test. I changed .OK to .not.OK and the test failed.

SS7 (Generating artefacts and adding filters)

This screenshot is a succesful execution of adding artefacts and filters.  
