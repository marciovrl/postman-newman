# Postman with Newman

## About
This project is to demonstrate a simple example of using the Postman with Newman. Tests are performed in [JsonPlaceholder](https://jsonplaceholder.typicode.com/) is a fake online REST API for testing and prototyping.

* [About](#About)
* [Preconditions](#Preconditions)
* [Local environment](#Local-environment)
    * [Configuration](#Configuration)
    * [Getting started](#Getting-started)
    * [Commands for running the tests](#Commands-for-running-the-tests)
* [Using docker](#Using-docker-environment)
    * [Configuration docker](#Configuration-docker)
    * [Commands for running the tests on docker](#Commands-for-running-the-tests-on-docker)
* [Report](#Report)
* [Links](#Links)

## Preconditions
-  [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

-  Clone the project: 
`git clone https://github.com/marciovrl/postman-newman.git`

## Local environment

### Configuration
- [Install node](https://www.techgalery.com/2019/12/how-to-install-nodejs-and-npm-on.html)

- [Install NPM](https://www.techgalery.com/2019/12/how-to-install-nodejs-and-npm-on.html)

- [Install Postman](https://www.postman.com/downloads/)

### Getting started

- Install dependencies: `npm install`

### Commands for running the tests
- Runs test suite: `npm test`
- Runs test suite with HTML report generate: `npm run test:report`

**Notes:** You can export to the Postman application.

## Using docker environment

### Configuration docker
- [Install docker](https://docs.docker.com/get-docker/)
- [Install docker-compose](https://docs.docker.com/compose/install/)

### Commands for running the tests on docker
- Build docker image with tests: `docker-compose build test`
- Run test on the docker: `docker-compose up test`

## Report

### Local report
After running the tests a report in HTML is automatically generated and stored in `results/report.html`.

## Links

### Postman Documentation
Official Postman support material [here](https://learning.postman.com/)